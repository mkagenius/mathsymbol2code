# mathsymbol2code

![x square](square.png)
```javascript
function square(x) 
{
    return x * x;
}
```

![product](prod.png)
```javascript
function prod(h)
{
    var ret = 1;
    for(var i in h)
    {
        ret *= h[i];
    }
    return ret;
}

var H = prod(h); // h is a 1-D array
```
![nested sum](nestedsum.png)
```javascript
function nestedSum(cost, 1, T, 1, N)
{
    var sum = 0;
    for(var i = 1; i <= T; i++)
    {
        for(var t = 1; t <= N; t++)
        {
            sum += cost[i][t];
        }
    }
    return sum;
}
P = nestedSum(cost, 1, T, 1, N) / N; // cost is a 2D array
```
