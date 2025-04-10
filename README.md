# 🌏 Trade & Industrial Development in East Asia  
**Independent Research | [LI JIAHUI] | Universiti Kebangsaan Malaysia**  

## 🔬 100% Self-Driven Study  
### 📊 Core Innovations  
- **首创变量**：首次将`FDI质量`指标纳入东亚分析体系  
- **方法突破**：  
  ```eviews
  ln(GDP)=β0​+β1​ln(Manufacturing Export)+β2​ln(High-Tech Export)+β3​ln(FDI)+β4​ln(1+Tariff Rate)+ϵ
## Dependent variable (Y) :
- Y=ln⁡(GDP) (logarithmic processing to reduce data scale differences).
## Independent variable (X) :
- X1=ln⁡(Manufacturing Export) : Manufacturing exports, expected to have a positive impact on GDP (β1>0).
- X2=ln⁡(High-Tech Export) : high-tech exports are expected to have a greater impact on GDP (β2>0).
- X3=ln⁡(FDI) : Foreign direct investment, representing capital inflows and technology spillovers (β3>0)
- X4=ln⁡(1+Tariff Rate) : trade barrier. Since this value is a percentage, logarithm will be negative if it is less than 1, so -we use ln⁡(1+Tariff Rate), which is expected to have a negative impact on GDP (β4<0).
- Error term (ϵ) : captures unobserved influencing factors, such as government policies, market conditions, etc.

高质量FDI的效益是普通FDI的2.3倍（β=0.68 vs 0.29）
高科出口对GDP贡献率达67.4%（p<0.01）

📂 Research Portfolio

手工收集2012-2021年面板数据[EastAsia_Trade_RawData.xlsx](https://github.com/user-attachments/files/19683789/EastAsia_Trade_RawData.xlsx)
- 覆盖中日韩马泰5国
- 含GNI/制造业出口/高科出口等变量

Regression_Models.wf1	EViews工作文件含：[EastAsia_Trade_Model.zip](https://github.com/user-attachments/files/19683794/EastAsia_Trade_Model.zip)
- 基准OLS模型
- 格兰杰因果检验
- 异方差White检验

Full_Paper.pdf	12页完整论文
- [EastAsia_Trade_Industrial_Development.pdf](https://github.com/user-attachments/files/19683791/EastAsia_Trade_Industrial_Development.pdf)

📊 Key Results Visualization
  Regression Summary[EastAsia_Trade_Regression Summary.xlsx](https://github.com/user-attachments/files/19686949/EastAsia_Trade_Regression.Summary.xlsx)

  高科出口 vs 传统制造业出口对GDP影响对比

🎯 Policy Implications
  东亚各国应建立FDI质量评估体系
  区域贸易协定需强化技术溢出条款

🖋️ Academic Statement
All data collection, analysis, and writing conducted independently by [LI JIAHUI].
Data sources: World Bank, UNCTAD, ASEAN Secretariat (2012-2021)

