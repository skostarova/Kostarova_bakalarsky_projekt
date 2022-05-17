# Kostarova_bakalarsky_projekt

## Analýza svetelných kriviek zákrytových premenných hviezd pomocou hlbokého učenia

### Skripty


Vytvorenie datasetov z pôvodných databáz:

1. vytvorenie súboru overcontact_Bessell_U.pkl pre experimenty 1, 2 a 3 - súbor [**data_overcontact_Bessell_U.ipynb**](data_overcontact_Bessell_U.ipynb)
2. vytvorenie súboru overcontact_one_curve.pkl - súbor [**data_overcontact_one_curve.ipynb**](data_overcontact_one_curve.ipynb) 
3. vytvorenie súboru detached_one_curve.pkl - súbor [**data_detached_one_curve.ipynb**](data_detached_one_curve.ipynb) 
4. vytvorenie súboru observed.csv - súbor [**data_observed.ipynb**](data_observed.ipynb)

Experimenty na predikciu pomeru efektívnych teplôt zo syntetických svetelných kriviek filtra Bessell_U bez umelého šumu:

5. experiment 1 = architektúra LSTM + 1D CNN č.1 - súbor [**LSTM_1DCNN_c1.ipynb**](LSTM_1DCNN_c1.ipynb)
6. experiment 2 = architektúra BiLSTM + 1D CNN - súbor [**BiLSTM_1DCNN.ipynb**](BiLSTM_1DCNN.ipynb)
7. experiment 3 = architektúra LSTM + 1D CNN č.2 - súbor [**LSTM_1DCNN_c2.ipynb**](LSTM_1DCNN_c2.ipynb)

Vizualizácia svetelných kriviek:

8. vizualizácia observačných a syntetických svetelných kriviek - súbor [**data_visualization.ipynb**](data_visualization.ipynb)

Predikcie pre dotykové systémy (overcontact):

9. predikcia pomeru efektívnych teplôt pre dotykové systémy - súbor [**overcontact_t2_t1.ipynb**](overcontact_t2_t1.ipynb) 
10. predikcia sklonu pre dotykové systémy - súbor [**overcontact_inclination.ipynb**](overcontact_inclination.ipynb)
11. predikcia pomeru hmotností pre dotykové systémy - súbor [**overcontact_mass_ratio.ipynb**](overcontact_mass_ratio.ipynb)
12. predikcia povrchového potenciálu pre dotykové systémy - súbor [**overcontact_pSP.ipynb**](overcontact_pSP.ipynb)
13. predikcie všetkých parametrov a ich vizualizácia pre dotykové systémy z observačných dát - súbor [**prediction_overcontact_observed.ipynb**](prediction_overcontact_observed.ipynb)

Predikcie pre oddelené systémy (detached):

14. predikcia pomeru efektívnych teplôt pre oddelené systémy - súbor [**detached_t2_t1.ipynb**](detached_t2_t1.ipynb)
15. predikcia sklonu pre oddelené systémy - súbor [**detached_inclination.ipynb**](detached_inclination.ipynb)
16. predikcia pomeru hmotností pre oddelené systémy - súbor [**detached_mass_ratio.ipynb**](detached_mass_ratio.ipynb)
17. predikcia primárneho povrchového potenciálu pre oddelené systémy - súbor [**detached_pSP.ipynb**](detached_pSP.ipynb)
18. predikcia sekundárneho povrchového potenciálu pre oddelené systémy - súbor [**detached_sSP.ipynb**](detached_sSP.ipynb)
19. predikcie všetkých parametrov a ich vizualizácia pre oddelené systémy z observačných dát - súbor [**prediction_detached_observed.ipynb**](prediction_detached_observed.ipynb)

### Datasety

1. dáta syntetických kriviek dotykových systémov - súbor **overcontact_one_curve.pkl** dostupný na https://mega.nz/file/5m43WQyK#G2WuLjqAkQT0OxQ4j-rZarCnmbtEx1rDQppiFNX8GdM
2. dáta syntetických kriviek oddelených systémov - súbor **detached_one_curve.pkl** dostupný na https://mega.nz/file/g3hVAKaT#NYCF7TzrOvn11laTDz5rTz3_dHnKClOfwhFzACepnig
3. dáta observačných kriviek - **observed.csv**
4. dáta pre experimenty 1, 2, 3 - súbor **overcontact_Bessell_U**
5. pôvodné dáta observačných kriviek - priečinok **krivky**
6. pôvodné databázy syntetických kriviek dotykových a oddelených systémov **overcontact.db** a **detached.db** dostupné na...?


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
