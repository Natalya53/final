Q1:

照ppt做

Q2:

・新增Class L3Cache

./configs/common/Caches.py

![image](https://github.com/user-attachments/assets/97703e3b-2aca-4fe2-b4fd-ef5d8713fe89)


・新增l3_cache_c_class,O3_ARM_v7aL3,l3_cache_class,L3Cache

./configs/common/CacheConfig.py


![image](https://github.com/user-attachments/assets/d8905f52-28fa-4ce3-9924-2426d5fa1087)

修改

![image](https://github.com/user-attachments/assets/75bcdd45-4414-48fc-a372-0bb1897b94c7)


・新增L3XBar

./src/mem/XBar.py

![image](https://github.com/user-attachments/assets/b88bb152-9b58-4159-8b04-74cdcfa9981a)


・修改"from XBar import L2XBar"

./src/cpu/BaseCPU.py

![image](https://github.com/user-attachments/assets/52e1eb8f-4138-43c2-91a4-fbf385f7d5be)

增加

![image](https://github.com/user-attachments/assets/79af4d99-311e-471c-8cd0-94f0ace0631f)

・加L3Cache

./configs/common/Options.py

![image](https://github.com/user-attachments/assets/ff9556a1-dfc7-4b17-917d-bf188b45e8db)


Q5:

