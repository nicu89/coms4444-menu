run:
	java -cp .:menu/org.json.jar menu.sim.Simulator --team random -m simpleConfig.dat -C 100 -p 3 -w 52 -s 42 -l log.txt -v -e meals.csv planners.csv pantries.csv satisfaction.csv

gui:
	java -cp .:menu/org.json.jar menu.sim.Simulator --team random -m simpleConfig.dat -C 100 -p 3 -w 52 -s 42 -l log.txt --gui -c -f 60

compile:
	javac -cp .:menu/org.json.jar menu/*/*.java

clean:
	rm menu/*/*.class
