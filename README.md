# hedgeR: Portfolio insurance strategies for commodity price risk management
Futures trading strategies for commercial hedgers with long or short exposure. All models below aim to reduce (increase) the commodity portfolio price, while preventing it from breaching a pre defined cap (floor).

### Commodity portfolio insurance strategy functions:

- cppi() - Constant Proportion Portfolio Insurance   
- dppi() - Dynamic Proportion Portfolio Insurance   
- obpi() - Option Based Portfolio Insurance         
- shpi() - Step Hedge Portfolio Insurance            
- vbpi() - VaR Based Portfolio Insurance             
- slpi() - Stop Loss Portfolio insurance             

Output S4 objects of type "cppi", "dppi", "obpi", "shpi", "vbpi" and "slpi", with methods "show", "summary" and "plot".

### Dynamic hedging strategies for
- Long and short hedgers
- Back testing and decision support for traded contracts

### Install from GitHub
```
install.packages("devtools")  
library(devtools)
install_github("sleire/hedgeR")
```
