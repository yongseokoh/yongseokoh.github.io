---
layout: post
title:  "CephFS MDS Slow Recovery Issue"
date:   2021-04-06 14:22:42 +0900
categories: CephFS
---



# MDS Logs

[mds001](https://drive.google.com/file/d/1r9GoSH7ZoMUcat8OH3tiOdRaXyVM-jBw/view?usp=sharing)
[mds002](https://drive.google.com/file/d/1qysVW9h5YhkHivYoijptFYSoHShGbKtg/view?usp=sharing)
[mds003](https://drive.google.com/file/d/1o0u6S1pGzroEN_HfDrzvdVFlwp0VLvwa/view?usp=sharing)
[mds004](https://drive.google.com/file/d/1TWFN_IGzBBT1hLCa25TM1E5pNVj9fgEg/view?usp=sharing)
[mds005](https://drive.google.com/file/d/1Ri7fU2AcwCzF3bdwnT7IjAWK-ufNlOu7/view?usp=sharing)



# MDS Metrics

![recovery time breakdown](/images/mds_restart/recvr-vdbench_m_mds_2_cch_16_caps_1000_strpl_cch_True_kernel_sessions_500_count_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
![recovey state count](/images/mds_restart/recvr-vdbench_m_mds_2_cch_16_caps_1000_strpl_cch_True_kernel_sessions_500_sum_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
![mds stat](/images/mds_restart/mds_stat_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
![reply rate](/images/mds_restart/mds_reply_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
![caps](/images/mds_restart/mds_caps_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
![inodes](/images/mds_restart/mds_inodes_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
![num_caps for sessoins](/images/mds_restart/num_caps_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
![release_capse for sessions](/images/mds_restart/release_caps_7183a8d9-38d1-4f99-a9c9-83edf44a27a1.png)
