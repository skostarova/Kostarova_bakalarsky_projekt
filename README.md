# Kostarova_bakalarsky_projekt

## Analýza svetelných kriviek zákrytových premenných hviezd pomocou hlbokého učenia

### Skripty

Vizualizácia svetelných kriviek:
1. vizualizácia observačných a syntetických svetelných kriviek - súbor **data_visualization.ipynb**

Predikcie pre dotykové systémy (overcontact):

2. predikcia pomeru efektívnych teplôt pre dotykové systémy - súbor **overcontact_t2_t1.ipynb** 
3. predikcia sklonu pre dotykové systémy - súbor **overcontact_inclination.ipynb**
4. predikcia pomeru hmotností pre dotykové systémy - súbor **overcontact_mass_ratio.ipynb**
5. predikcia povrchového potenciálu pre dotykové systémy - súbor **overcontact_pSP.ipynb**
6. predikcie všetkých parametrov a ich vizualizácia pre dotykové systémy z observačných dát - súbor **prediction_overcontact_observed.ipynb**

Predikcie pre oddelené systémy (detached):

7. predikcia pomeru efektívnych teplôt pre oddelené systémy - súbor **detached_t2_t1.ipynb**
8. predikcia sklonu pre oddelené systémy - súbor **detached_inclination.ipynb**
9. predikcia pomeru hmotností pre oddelené systémy - súbor **detached_mass_ratio.ipynb**
10. predikcia primárneho povrchového potenciálu pre oddelené systémy - súbor **detached_pSP.ipynb**
11. predikcia sekundárneho povrchového potenciálu pre oddelené systémy - súbor **detached_sSP.ipynb**
12. predikcie všetkých parametrov a ich vizualizácia pre oddelené systémy z observačných dát - súbor **prediction_detached_observed.ipynb**

Experimenty na predikciu pomeru efektívnych teplôt zo syntetických svetelných kriviek filtra Bessell_U bez umelého šumu:

13. experiment 1 = architektúra LSTM + 1D CNN č.1 - súbor **LSTM_1DCNN_c1.ipynb**
14. experiment 2 = architektúra BiLSTM + 1D CNN - súbor **BiLSTM_1DCNN.ipynb**
15. experiment 3 = architektúra LSTM + 1D CNN č.2 - súbor **LSTM_1DCNN_c2.ipynb**

### Datasety

1. dáta syntetických kriviek dotykových systémov - 
2. dáta syntetických kriviek oddelených systémov -
3. dáta observačných kriviek - **observed.csv**
4. dáta pre experimenty 1, 2, 3 - 


### Modely

1. model pre predikciu pomeru efektívnych teplôt pre dotykové systémy - súbor **overcontact_sT_pT.hdf5** 
2. model pre predikciu sklonu pre dotykové systémy - súbor **overcontact_inclination.hdf5**
3. model pre predikciu pomeru hmotností pre dotykové systémy - súbor **overcontact_mass_ratio.hdf5**
4. model pre predikciu povrchového potenciálu pre dotykové systémy - súbor **overcontact_pSP.hdf5**
5. model pre predikciu pomeru efektívnych teplôt pre oddelené systémy - súbor **detached_sT_pT.hdf5**
6. model pre predikciu sklonu pre oddelené systémy - súbor **detached_inclination.hdf5**
7. model pre predikciu pomeru hmotností pre oddelené systémy - súbor **detached_mass_ratio.hdf5**
8. model pre predikciu primárneho povrchového potenciálu pre oddelené systémy - súbor **detached_pSP.hdf5**
9. model pre predikciu sekundárneho povrchového potenciálu pre oddelené systémy - súbor **detached_sSP.hdf5**
10. model architektúry LSTM + 1D CNN č.1 - súbor **sT_pT_over_lstm_1dcnn_c1.hdf5**
11. model architektúry BiLSTM + 1D CNN - súbor **sT_pT_over_bilstm.hdf5**
12. model architektúry LSTM + 1D CNN č.2 - súbor **sT_pT_over_lstm_1dcnn_c2.hdf5**

---
### *Silvia Kostárová, Bakalárska práca* 

Hospodárska informatika, KKUI, FEI TUKE 2022
