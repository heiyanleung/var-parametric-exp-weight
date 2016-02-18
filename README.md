# var-parametric-exp-weight
Value at Risk: parametric exponentially weighted

Parametric VaR with exponentially weighted moving average works very similarly
to its equally weighted counterpart. Only this time, we need to also specify the
decay factor lambda, lamb.

MyVarParEx(port=port,wei=e.weight,comp.days=1,size.days=251,conf=0.95,lamb=0.97)
