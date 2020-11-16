# bigdata-spark-runner


## Commands:
 ```curl "https://www.dailyscript.com/scripts/Godfather,%20The.txt" -o "godfatherI.txt"```

 ```sed -e 's/I / /g;s/ am / /g;s/ you / /g;s/The / /g;s/ the / /g;s/ an / /g;s/ a / /g;s/ in / /g;s/ at / /g;s/ on / /g; s/ is / /g;s/ are / /g; s/Is / /g; s/Are / /g' godfatherI.txt > godfatherI_cleaned.txt```



```cd "your directory"```
```python -m wordcount --input godfatherI_cleaned.txt --output outputWordCount```
```python -m wordcount --input godfatherI_cleaned.txt --output output --runner SparkRunner```