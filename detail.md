# 데이터셋 정보

| 컬럼                         | 컬럼설명                                            | dtype       | train 결측값(%) | valid 결측값(%) | test 결측값(%) |
| ---------------------------- | --------------------------------------------------- | ----------- | --------------- | --------------- | -------------- |
| id                           | 아이디                                              |             |                 |                 |                |
| dt_of_fr                     | 화재발생일시                                        | 시계열      | 0               |                 | 0              |
| fr_yn                        | 화재발생여부                                        | Y/N         |                 |                 |                |
| bldng_us                     | 건물용도                                            | categorical | 46.7525         |                 | 15.9           |
| bldng_archtctr               | 건물구조                                            | categorical | 46.7322         |                 | 15.6           |
| bldng_cnt                    | 건물채수                                            | numerical   | 0               |                 | 0              |
| bldng_ar                     | 건물건축면적                                        | numerical   | 0               |                 | 0              |
| ttl_ar                       | 건물연면적(건물층별합계전체 면적)                   | numerical   | 0               |                 | 0              |
| lnd_ar                       | 토지면적                                            | numerical   | 0               |                 | 0              |
| dt_of_arthrztn               | 건물승인일자                                        | 시계열      | 46.5903         |                 | 15.6           |
| ttl_grnd_flr                 | 건물들의 지상 층수의 합                             | numerical   | 17.2469         |                 | 11.6           |
| ttl_dwn_flr                  | 건물들의 지하 층수의 합                             | numerical   | 18.5898         |                 | 13.5           |
| bldng_us_clssfctn            | 건물용도분류명                                      | categorical | 49.5667         |                 | 23.2           |
| tmprtr                       | 온도(c)                                             | numerical   | 0.0219          |                 | 0.03           |
| prcpttn                      | 강수량                                              | numerical   | 90.5911         |                 | 92.7           |
| wnd_spd                      | 풍속                                                | numerical   | 0.0557          |                 | 0.03           |
| wnd_drctn                    | 풍향                                                | numerical   | 0.3733          |                 | 0.13           |
| hmdt                         | 습도                                                | numerical   | 0.0372          |                 | 0.07           |
| ele_engry_us_201401          | 전기 에너지 사용량(2014월1월)                       | numerical   | 46.5903         |                 | 15.6           |
| gas_engry_us_201401          | 가스 에너지 사용량(2014월1월)                       | numerical   | 46.5903         |                 | 15.6           |
| ...                          | ...                                                 |             | ...             |                 | ...            |
| lw_13101010                  | 복도,계단,출입구의 성능 유지여부(0~5)               | numerical   | 99.4899         |                 | 98.6473        |
| lw_13101110                  | 옥상광장의 피난성능 유지여부(0~5)                   | numerical   | 99.5084         |                 | 98.6473        |
| lw_13101210                  | 방화문, 방화셔터 등의 성능 유지여부(0~5)            | numerical   | 99.4983         |                 | 98.6473        |
| lw_13101211                  | 방화구획 적합 여부(0~5)                             | numerical   | 99.4966         |                 | 98.6473        |
| lw_13101310                  | 경계벽 및 칸막이벽의 변경 등 방화성능 유지여부(0~5) | numerical   | 99.5067         |                 | 98.6473        |
| lw_13101410                  | 배연설비의 성능 유지여부(0~5)                       | numerical   | 99.522          |                 | 98.6473        |
| lw_13111010                  | 내화구조의 성능 유지여부(0~5)                       | numerical   | 99.4932         |                 | 98.6473        |
| lw_13111110                  | 방화벽의 성능 유지여부(0~5)                         | numerical   | 99.5253         |                 | 98.6473        |
| lw_13121010                  | 외벽의 성능 유지여부(0~5)                           | numerical   | 99.5388         |                 | 98.6473        |
| lw_13121011                  | 창호의 성능 유지여부(0~5)                           | numerical   | 99.5388         |                 | 98.6473        |
| lw_13131010                  | 내부마감의 방화성능 유지여부(0~5)                   | numerical   | 99.5            |                 | 98.6473        |
| lw_13131110                  | 외부마감의 노후화 및 마감재 탈락 여부(0~5)          | numerical   | 99.5            |                 | 98.6473        |
| lw_13141010                  | 지하층의 소방설비 성능 유지여부(0~5)                | numerical   | 99.5067         |                 | 98.6473        |
| lw_13141011                  | 지하층 피난구,피난계단의 성능 유지여부(0~5)         | numerical   | 99.5084         |                 | 98.6473        |
| jmk                          | 지적상 지목                                         | categorical | 0               |                 | 0              |
| rgnl_ar_nm                   | 용도지역지구명                                      | categorical | 2.5186          |                 | 1.39           |
| rgnl_ar_nm2                  | 용도지역지구명2                                     | categorical | 2.5186          |                 | 1.39           |
| lnd_us_sttn_nm               | 토지이용상황명                                      | categorical | 3.000           |                 | 2.47           |
| rd_sd_nm                     | 도로측면명                                          | categorical | 2.5186          |                 | 1.39           |
| emd_nm                       | 행정구역명                                          | categorical | 0.0068          |                 | 0              |
| hm_cnt                       | 행정구역 인구                                       | numerical   | 1.1841          |                 | 0              |
| fr_sttn_dstnc                | 소방서로부터의 거리                                 | numerical   | 0               |                 | 0              |
| fr_sttn_dstnc_119            | 안전센터와의 거리                                   |             |                 |                 |                |
| bldng_ar_prc                 | 단위 면적당 건물 가격                               | numerical   | 36.9854         |                 | 45.5           |
| fr_wthr_fclt_dstnc           | 소방용수시설(소화전 등)과의 거리                    | numerical   | 0               |                 | 0              |
| fr_mn_cnt                    | 관할 소방서 인원                                    | numerical   | 0.0693          |                 | 0              |
| mlt_us_yn                    | 다중이용시설 포함여부                               | categorical | 0               |                 | 0              |
| cctv_dstnc                   | 공공 CCTV와의 최소 거리                             | numerical   | 0               |                 | 0              |
| cctv_in_100m                 | 100m 이내 공공 CCTV                                 | numerical   | 0               |                 | 0              |
| fr_wthr_fclt_in_100m         | 100m 이내 소방용수 시설 수                          | numerical   | 0               |                 | 0              |
| tbc_rtl_str_dstnc            | 담배 소매점과의 최소 거리                           | numerical   | 0               |                 | 0              |
| sft_emrgnc_bll_dstnc         | 안전 비상벨과의 최소 거리                           | numerical   | 0               |                 | 0              |
| ahsm_dstnc                   | 자동 심장 충격기와의 최소 거리                      | numerical   | 0               |                 | 0              |
| no_tbc_zn_dstnc              | 금연구역과의 최소 거리                              | numerical   | 0               |                 | 0              |
| bldng_cnt_in_50m             | 반경 50M 이내의 건물 수                             | numerical   | 0               |                 | 0              |
| trgt_crtr                    | 소방점검대상물기준                                  | categorical | 86.1873         |                 | 92.1           |
| fr_fghtng_fclt_spcl_css_5_yn | 소방시설특례5호여부                                 | categorical | 85.7481         |                 | 81.2           |
| fr_fghtng_fclt_spcl_css_6_yn | 소방시설특례6호여부                                 | categorical | 85.7481         |                 | 81.2           |
| us_yn                        | 사용여부                                            | categorical | 83.5267         |                 | 78.4           |
| dngrs_thng_yn                | 위험물대상여부                                      | categorical | 83.5267         |                 | 78.4           |
| slf_fr_brgd_yn               | 자체소방대여부                                      | categorical | 83.5267         |                 | 78.4           |
| blk_dngrs_thng_mnfctr_yn     | 대량위험물제조소등여부                              | categorical | 83.5267         |                 | 78.4           |
| cltrl_hrtg_yn                | 문화재여부                                          | categorical | 83.5267         |                 | 78.4           |



# 이상치 검출

| column        | id    | 수정전  | 수정후   |
| ------------- | ----- | ------- | -------- |
| dt_of_athrztn | 26351 | 9990624 | 19990624 |
| dt_of_athrztn | 21218 | 9900712 | 19900712 |
| dt_of_athrztn | 30954 | 9820930 | 19820930 |
| dt_of_athrztn | 12642 | 9800808 | 19800808 |
| dt_of_athrztn | 38448 | 9780421 | 19780421 |
| dt_of_athrztn | 53193 | 971215  | 19971215 |
