To be honest, I am not so clear about this question. So this is just my opinion.

DFT(data flow testing) is used to verify the correct handling of data relations and dependencies during program execution. And it is DDGs used in slice testing make DFT different from CFT. During a synchronization testing, for example, C should be triggered by A and B, and B is relied by the output of A. So the subject of DFT should be to ensure only A->B, A+B ->C is feasible. If there is only A and not B, C can not be produced. Neither nor there is only B not A. 

