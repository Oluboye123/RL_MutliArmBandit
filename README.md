# RL_MutliArmBandit


#Consider a bank of 10 slot machines, with the agent's goal being to maximise winnings
#while minimising losses.
#The agent takes some chances at start because it has no idea what the reward probability 
#of any of the machines is.The agent wins and earns a payoff on the first pull of the lever.
#Repeated attempts demonstrate that this machine pays out roughly half of the time
#The code generates an array of rewards ranging from 0.004 to 0.844 for a set of 
#10 slot machines and the agent's first machine was generous, it was not the best.
#the fourth slot machine with an 84.4 percent payout rate is the best paying machine in the environment
#It is worth noting that the fifth slot machine has the worst odds of paying out a jackpot. 
#The agent has no prior knowledge of the payout rates and it must discover them on its own. 
#Had the agent stayed on the first machine, choosing exploitation over exploration, 
#the agent would never have found the best paying slot machine
