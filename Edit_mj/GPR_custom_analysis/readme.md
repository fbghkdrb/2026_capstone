## GPR_custom_analysis 파일 내 참조 내용

1. GPR_custom_analysis.ipynb : 수집 및 전처리 총 정리 파일
2. correlation.ipynb : 상관관계 30, 60, 90일 단위로 파악
3. total_custom_gpr_final.csv : total 전처리 후 custom_gpr 저장 파일  
4. gpr_combined.csv : total_gpr 표준화된 파일  
5. gpr_correlation_summary.csv : 상관관계 별 결과값  

-----------
## master_data_generated 파일 내 참조 내용  

1. master_data_generated.ipynb : custom+ gpr+ 자산 및 지수 통합 수집 및 전처리 로직  
2. returns.csv : date,BTC,Gold,TLT,DXY,SP500,NASDAQ 에 대한 일자별 표준화 값  
3. master_data.csv : date	event_name	event_date	GPR_custom	F3_raw	GPR	GPR_zscore	N	mean_tone	BTC	Gold	TLT	DXY	SP500	NASDAQ	VIX	fear_greed	fg_label	fear_greed_lag1	해당 컬럼 값 최종 파일  
- 이미지 첨부  
<img width="2080" height="33" alt="image" src="https://github.com/user-attachments/assets/4878ff46-d8db-4465-82d5-5158930da644" />
