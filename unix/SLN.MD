awk -F, ' {a[$3]+=$4;} 
END {for (i in a) print i", "a[i];}' 
employee.csv 