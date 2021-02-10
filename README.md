# Integer To Roman 
This project contains the spring boot application of Integer to Roman 
Given an integer within range(1-3999) the application will give the Roman value 


#The Application supports two queries 

##Input : localhost:8080/romannumeral?query=1

##Output :


##Input : localhost:8080/romannumeral?min=1&max=3
##Output :



#Steps to run the application 
-- Running as Docker contaner 
        -- Clone the repo into any of the directory (Example C:/adobe)
        -- Change into directory C:/adobe
        -- simple check . Execute "ls" command to see "src" directory, pom.xml, Dockerfile
        --  execute mvn clean install (please check if maven is installed or not) if not please install maven ans yd then execute the next steps
        -- run "ls" command and you can see "target" folder created
        -- docker build -t <tagname> . (you can provide any tag) for example docker build -t adobe.
        -- docker ps -a  or docker images gives you list of docker immages that are running and you can see tagged(adobe) is also presnet
        -- docker run -p 8080:8080 -t <tagname> . example docker run -p 8080:8080 -t adobe.
        -- this will run the application on 8080
        ```mvn clean install
           docker bu,ild -t adobe .
           docker run -p 8080:8080 -t adobe .
        ```
##Contributing
Pull requets are welcome. For major changes please drop a comment 


