build
test
monitor
troubleshoot
utilities


## useful expression

	Almost one million downloads every month.
	Wireshark enables engineers to get to the packet of a problem quickly.
	This allows them quickly determine if the issue is due to the internet, server, or client. Rather than guess the cause of the problem.
	They can utilize the Wireshark to see the real truth.
	The packet output can be a challenge to read.
	especially for those new traffic analysis
	The voice is very clear, and the explanation is quite understandable. Thank you.
	The following are some of the many features Wireshark provides
	 Wireshark might help you figure out what is really going on.


## bash note
		# while statement
		COUNTER=0
		while [ $COUNTER -lt 10 ]; do
		  echo The counter is $COUNTER
		  let COUNTER+=1 
		done
		
		# until statement
		COUNTER=20
		until [ $COUNTER -lt 10 ]; do
		  echo The counter is $COUNTER
		  let COUNTER-=1 
		done
		
		# for statement
		for i in 1 2 3 4 5
		do
		   echo "Welcome $i times"
		done
		# for statement
		for i in {1..10}
		do
		   echo "Welcome $i times"
		done
		# for statement
		echo "Bash version ${BASH_VERSION}"
		for i in $(seq 1 2 20)
		do
		   echo "Welcome $i times"
		done
		# for statement
		for i in $(ls ./ -ah)
		do
		  echo "Welcome $i times"
		done
		
		# if condition statement
		yourname=steven
		if [ $yourname == bowentang ]
		then
		echo "welcome back, $yourname"
		elif [ $yourname == nicole ]
		then
		echo "welcome back, my wife, $yourname"
		else [ $yourname == steven ]
		echo "welcome back, my colleague, $yourname"
		fi


		# case esac statement
		echo -n "Enter the name of an animal: "
		read ANIMAL
		echo -n "The $ANIMAL has "
		case $ANIMAL in
		(horse | dog | cat) 
		    echo -n "four";;
		(man | kangaroo ) 
		    echo -n "two";;
		(*) 
		    echo -n "an unknown number of";;
		esac
		    echo " legs."