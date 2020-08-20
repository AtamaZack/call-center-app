# Call Center App

This is a data analysis application that helps a call center to analyze data from the customer care service department. The application takes in **.csv** file containing call records and creates usefull data charts that can easily be interprated.

### Features
----
- Display number of customers who called in multiple times in a 2 weeks period and their call topics.
- Display call statistics per region.
- Display call statistics per CSR
- Display call statistics per call topic group. - *(Suggestion)*

### File Data Structure
----
```
{
	data: [
		'call_id',
		'destination_person_id',
		'source_person_id',
		'account_age',
		'account_state',
		'occupation',
		'language',
		'call_direction',
		'call_duration',
		'call_outcome',
		'call_end_date',
		'call_topics',
		'call_topic_group'
	]
}
```
### Data Charts
----
- Calls Per Week *(Bar Chart)*
- Calls per Region *(Bar or Pie Chart)*
- Calls per Topic Group *(Pie Chart)*

### Tables
----
- Calls per CSR - 2 Tables *(Incoming and Outgoing)*

##### Incoming Calls Table
CSR Person Id  | Number of Calls | Percentage of Calls | Total Calls Duration
------------- | ------------- | ------------- | -------------
Content Cell  | Content Cell | Content Cell  | Content Cell
Content Cell  | Content Cell | Content Cell  | Content Cell

##### Outgoing Calls Table
CSR Person Id  | Number of Calls | Percentage of Calls | Total Calls Duration
------------- | ------------- | ------------- | -------------
Content Cell  | Content Cell | Content Cell  | Content Cell
Content Cell  | Content Cell | Content Cell  | Content Cell
