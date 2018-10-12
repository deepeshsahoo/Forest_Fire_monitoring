# Forest_Fire_monitoring
Microsoft CodeFunDo ++

Problem Statement:

	Real time detection and monitoring of forest fires using wireless sensor networks.

Overview:
	
	The forest fire can be detected by a temperature sensor when the temperature crosses a 	certain threshold and the humidity decreases with time. Regions of the forest can be covered 	with sensor motes equipped with temperature and humidity sensors, GPS trackers and/or use	energy harvesting sources. These sensor motes comunicate to their cluster heads over a radio 	frequency. The clusters then transmit the data over the Azure network to be analysed.

Data:

	The real-time data will help in the following ways:
1. Finding the intensity of the forest fire at specific regions. Cutting of the fire at high intensity regions is likely to reduce the time taken to dose the fire off completely. This also reduces the burden as to which place to start with at dosing out the flames
2. Using the temperature and humidity at nearby locations, find regions where the fire may spread first. This helps in limiting the fire from spreading to nearby regions, hence restricting the fire to a given region, allowing the situation to be dealt with more ease.
3. Over time, analysing the start of forest fires with the existing data can help in preventing  a fire before it actually starts. As we collect more data, it is possible to run learning algorithms with the current data sets to predict the start of forest fires.
4. Based on the rate of fire, villages/residents in the possible range of extent of the fire can be informed on a prior basis.

Workflow:

	The sensors collect data and transmit it to the cluster nodes perodically. The cluster nodes
	push the data to the cloud. The cloud computes all the data and based on the threshold, 
	detects fire at select places. When fire is detected, the concerned authorities are alerted.
	Real time data allows the concerned departments to be prepared without being close to the 
	location.
