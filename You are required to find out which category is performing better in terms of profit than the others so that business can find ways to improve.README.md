select Category, SUM(PROFIT) FROM orders 
GROUP BY Category ORDER BY SUM(PROFIT) DESC;
