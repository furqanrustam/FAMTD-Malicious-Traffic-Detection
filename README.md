FAMTDS: A novel MFO-based fully automated malicious traffic detection system for multi-environment networks

Multi-environment networks, such as those in smart homes, handle both IoT and traditional IP-based traffic. Weak security protocols in IoT devices and the diverse traffic flow make these networks vulnerable to security breaches. This study delves into this pressing challenge and presents a pioneering solution—FAMTDS (Fully Automated Malicious Traffic Detection System)—designed explicitly for multi-environment networks. FAMTDS addresses the critical need for robust security measures by intelligently analyzing the amalgamation of IoT and IP-based traffic. FAMTDS comprises three pivotal stages: innovative multi-environment dataset creation, optimization of machine learning model hyperparameters, and holistic system optimization. For the multi-environment dataset, we amalgamate two prominent open-source datasets, UNSW-NB-15 and IoTID-20. Initially, crucial features are extracted from both datasets using an extra trees classifier. Subsequently, an equal number of features is generated by employing a neural network to harmonize these datasets. The resulting multi-environment dataset encompasses 19 distinct attack types, a comprehensive inclusion unprecedented in prior research on malicious traffic detection. This dataset exhibits diversity owing to its varied traffic samples, addressing a crucial gap in existing studies. To accommodate this diversity, machine learning models are deployed with fine-tuned hyperparameters. The Mouth Flame Optimizer streamlines feature extraction, feature generation, and hyperparameter tuning, automating the optimization process. FAMTDS demonstrates exceptional performance, achieving an accuracy score of 0.85 for the multi-environment dataset. We also integrated the CICDDOS2019 dataset with IoTID-20 in our multi-environment dataset, achieving a notable accuracy of 0.82 against recent attacks, thus enhancing our approach’s validation. To further validate the generalizability of our proposed approach, we applied it to zero-day attack prediction. Our method demonstrated an accuracy of 0.84 for zero-day attacks, indicating its effectiveness in detecting newly emerging threats in multi-environment networks.
