Queens: Queens.class
	echo Main-class: Queens > Manifest
	jar cvfm Queens Manifest Queens.class
	rm Manifest
	chmod u+x Queens

Queens.class: Queens.java
	javac -Xlint Queens.java

clean: Queens.class
	rm -f Queens.class Queens
  


#check number of char
#expected usage Queens -v n or Queens n
#if(args.length == 2 ...implies -v n    => case 1
#if(args.length == 1 ...implies n)  => case2


#case 1:
#you expect args[0] = "-v" and rgs[1] = number n
#check args[0].equals("-v")
#for rgs[1], use try and catch
#you need to validat that this is the case

#case 2:
#expect args[0] = be a number
