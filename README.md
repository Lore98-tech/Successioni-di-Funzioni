#README

This code plot functions y = f(x, k), where x is real and k is a natural number.
To run the code, define a function in Successioni_di_funzioni.py. If possible, k starts from 0 or 1. 
Then you can choose where to stop k, the plot interval on x axis, and a color palette.
Moreover, there is the possibility to plot the derivates of the functions. 
The plot limit on y axis is defined as a constant in function.py and can be changed. 

List of functions:
y = np.sin(np.power(x, 2)/k)
y = np.sin(k *x)
y = np.power(np.power(k*x, 2) + 1, 1/2) - np.power(np.power(k*x, 2) - 1, 1/2)
y = x/(1 + k * x)
y = x/(1 + np.power(k*x, 2))
y = np.power(k*x, 2)/(1 + np.power(k*x, 2))
y = np.power((np.power(x, 2) - x),k)
y = k*k/x
y = np.sin(np.power(x, 2)/k) + (1 - np.power(1 - np.power(x, 2), 1/2))/k #[-1; 1]
y = (k * np.power(x, 3) + np.power((k + 1), 2) * np.sin(x))/(1 + np.power(k, 2)) #[-1; 1]
y = np.power(k, 3)/(np.power(k, 1) * 2 * x) * np.sin(x) + x * np.power((k + 1), 2)/(1 + np.power(k, 2)) - np.log(k * np.abs(x))
y = np.sin(x - k/2) 
y = np.cos(x - k/2) - k*np.log(k + 1)/(k - 20.5) * np.log(x)
y = np.sin(k/30)*k/100*np.exp(-x*x/np.abs(k-k*np.sin(k/10)))
y = 1/x*np.sin(k/30)
y = np.sin(x + np.sin(k/50)*20*k/(k+20))*np.cos(x)
y = 10*np.sin(x + k/10) + k*np.cos(k/10)