# Machine_fault_detection_using-_sound_analysis
Machine  fault  detection  in  noisy  industrial  environments, is  crucial  for  ensuring 
operational  safety  and  efficiency.  This  research  presents  a  model  fault 
detection  system  that  uses  an  ESP32  dev  module  development  module 
and  a  sound  sensor  to  monitor  and  identify  abnormal  noise  levels 
indicative  of  potential  faults.  The  system  detects  sounds  exceeding  a 
predefined  threshold,  representing  deviations  from  normal  machine 
operation  noise  levels.  Upon  detecting  anomalies,  the  system  transmits 
the data to a server over a WiFi network. 
A  Python-based  Flask  application  hosted  on  the  server  processes  and 
stores  the  incoming  data  in  a  MySQL  database.  The  server  is  accessible 
only  to  devices  connected  to  the  same  network  (e.g.,  office  WiFi)  to 
ensure  security.  The  web  interface,  developed  using  Chart.js,  provides 
real-time  sensor  data  visualization,  displaying  current  values,  historical 
trends,  and  fault  occurrences  highlighted  in  red.  The  system  also 
generates  alerts  for  noise  levels  surpassing  the  threshold,  which  are 
logged in the database and displayed on the web interface. 
This  model  fault  detection  system  is  crucial  for  preventing  machinery 
breakdowns,  minimizing  downtime,  and  enhancing  personnel  safety  by 
enabling  timely  maintenance  and  intervention.  Extensive  testing 
.demonstrates  the  system's  effectiveness  in  accurately  detecting  faults, 
ensuring  timely  data  transmission,  and  maintaining  robust  database 
management.
