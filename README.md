# learn_linux_by_doing
list of commands used
rm test-1
mv top-5-lowest temperatures.csv analyzed
mv top5-highest-temperatures.csv top-5-highest-temperatures.csv
grep "Ethiopia" satelite_temperature_data.csv | cut -d ',' -f 1-3 >country-heat_data.csv
sort -u satelite_temperature_data.csv > temp.txt && mv temp.txt satelite_temperature_data.csv
cat satelite_temperature_data.csv | cut -d" -f1-3 | sort -n | head -n 5 > ../analyzed/ top-5-lowest-temperatures.csv
