﻿# Explaining the syntax of an if statement 

```csdiff
protected override void OnSavingRow()
{
-   if (Orders.OrderDate.Year < 1990)
+   if (Orders.OrderDate.Year < 1990 || Orders.OrderDate.Year>2020)
    {
        Message.ShowError("Invalid Year");
    }
}
```
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/ILv1m8NA2sM?list=PL1DEQjXG2xnL1VKb5GvdDwxJeym7Uj6S3" frameborder="0" allowfullscreen></iframe>
