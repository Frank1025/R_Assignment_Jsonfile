# R_Assignment_Jsonfile
browseURL("http://citibikenyc.com/stations/json")
city<-fromJSON("http://citibikenyc.com/stations/json")
str(city)
stations<-city$stationBeanList
colnames(stations)
is.data.frame(stations)
stationName<-city$stationBeanList$stationName
stationName
is.atomic(stationName)
plot(id)
# It seems to me that there's a limit to the amount of output the console can display.Please is that the case? @ Edison.
