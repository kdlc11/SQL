SELECT item_name, price
FROM superstore
ORDER BY price ;

SELECT AVG(average_rating), item_name
FROM superstore
GROUP BY item_name DESC;

SELECT MAX(stock_quantity), item_name 
FROM superstore
WHERE category='Kitchen Supplies'
GROUP BY item_name;

SELECT SUM(stock_quantity), item_name
FROM superstore
GROUP BY item_name;
