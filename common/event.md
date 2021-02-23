# Event

### Manage Event

Most of the activities happened in startup ecosystem can be broken down and categorized as Event. Tracking event allows ecosystem builder to understand the development of the entire ecosystem.

### Search & View Event

### Event Group

Multiple events can be group under 1 Event Group. For example, a 'MaGIC Accelerator Program' is an event group with the following events:

* MaGIC Accelerator Program 2015
* MaGIC Accelerator Program 2016
* MaGIC Accelerator Program 2017

### Create Event

### Update Event

### Event Owners

### Event Registrations

Event registration keeps track of individuals who participated in an event.

These data can be sync thru modules like `Eventbrite` and `Bizzabo`. It can also be manually bulk loaded using spreadsheet. \(todo: attach link of the spreadsheet template here\).

#### Manually a**dd Events Attendance \(Individual Participants\)**

### Event Organisations

Event Organization keeps track of companies/organizations who participated in an event. For examples, an event would be organised by `MaGIC` and `Ministry of Technology`, sponsored by `Google` and `Facebook`, with judges came from `Multimedia University` and `Startup Melaka`.

#### Manually a**dd Events Attendance \(Organisation Participants\)**

### Surveys

When enabled, CENTRAL automatically email survey link to attended participants a day after the event ended. 

* Event has to be active and not cancel
* Setting `event-sendPostSurveyEmail` must be turned on
* Hourly cron job is set to trigger the command `php yiic emailSurveyAfterEvent oneDayAfter`
* Respective F7 form must exist

### Sync from Eventbrite

### Link with Resource

