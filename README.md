**Intrusion-Detection-System-IDS-in-Internet-of-Vehicles-IOV---Tree-Algorithms-DT-ET-RF-XGBoost**
_________________________________________________________________________________________________
![intrusion](https://user-images.githubusercontent.com/32153763/233834001-dec9bdcc-f6fc-4c68-9300-f07dfbf9258e.png)

______________________________________________________________________________________________________
1. Intrusion Detection System **`[IDS]`** in Internet of Vehicles **`[IOV]`** --- Tree Based ALGORITHMS

2. **`[AV]`** Autonomous Vehicle + **`[IOV]`** *Internet of vehicle = ***`[ITS]`** Intelligent Transport Systems

3. **`[AV]`** = **`[V2X]`** Vehicle to Public **`[V2P]`**, Vehicle **`[V2V]`**, Infra **`[V2I]`**

4. **`[IDS]`** <-- **`[AV]`** + **`[IOV]`** <-- External /Internal Communication Threat

 **Dataset:** **`CICID 2017`** - Standard Attack Scenario___________________ [28,30,743 x 79]

 **Pre Processing :** Normalization ,Encoder_____________________________[56,661 x 79]

 **Oversampling :** **`SMOTE`** <-- Handle Class Imbalance Data __{4 :1500}

**Models**

| **Model**          | **Accuracy**            |**Acc(with Imp Feature)**|
| ---------------| ------------------- | ----- |              
|`Decision Tree`  :| 99.67 %             |99.68 %|
|`Random Forest`  :| 99.62 %             |99.74 %|
|`Extra Trees`    :| 99.53 %             |99.64 %|
|`XGBoost`        :| 99.55 %             |99.53 %|
|**`Stack`**          :| **96.63 %**             |**99.63 %**|

![Results](https://user-images.githubusercontent.com/32153763/233833669-8e04a0a5-2b1d-4ee0-97ff-9b7d02c5fc6e.png)

