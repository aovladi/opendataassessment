# opendataassessment
Assessment of russian open data portal


Steps to run program </br>
</br>
1.	 Register on data.gov.ru and get your own API key</br>
2.	 Install mysql database</br>
3.	 Create database </br>
4.	 Run sql scripts dataset.sql , organization.sql, topics.sql</br>
5.	 Install NetBeans</br>
6.	 Put downloaded folder EN into NetBeansProjects (usually it is in C:\Users\<your user_name>\Documents\NetBeansProjects)</br>
7.	 Open EN project in NetBeans</br>
8.	 in main package open Work.java and interfacee.java</br>
</br>
Work.java</br>
1.	insert your api key in line 44 (public static String APIkey = "?access_token=...";)</br>
2.	in start_conn() insert all parametrs for your database</br>
</br>
interfacee.java</br>
1.	lines 47-49: insert parametrs to connect your database </br>
variable connection should look like "jdbc:mysql://localhost:3306/<database name>"
