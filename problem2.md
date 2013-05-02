P = Primes();
P <= 10^7

n=15
for i in P:
    data=mod(i,n)

data
stats.TimeSeries([random() for _ in range(data)]).plot_histogram()
