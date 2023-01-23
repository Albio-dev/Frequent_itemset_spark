# Frequent_itemset_spark

ToDo:
- [X] 1. generare tutti i possibili itemset dal basket 
- [X] 2. ritornare gli itemset frequenti nel basket <br>
        a. Filtrare gli itemset frequenti di ogni basket e ritornare solo quelli massimali
        b. Vedere ti cominciare il ciclo già dalle coppie
- [ ] 3. per ogni itemset candidato contare le occorrenze nel basket
- [ ] 4. sommare le occorrenze di ogni basket e calcolare il supporto totale

bonus:
 - Controllare la composizione e la suddivisione delle partizioni 
 - Distribuire il calcolo della dimensione di ogni partizione (no lista)
 - Benchmark esecuzione ed individuare bottleneck
 - Fare una compilazione degli item in numeri