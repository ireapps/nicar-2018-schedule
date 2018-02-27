| **Field** | **Definition** | **Comments** |
| --- | --- | --- |
| event_id | The event id assigned by the IRE events management system. | Example: Can be used in conjunction with the link https://www.ire.org/events-and-training/event/3189/[event_id] to see online event.|
| name | The name of the session.| |
| clean_description | The description of the session.| This comes from the IRE events management system and is free of HTML tags. |
| location_room | The room where the session is being held.|  |
| start_date_clean | The date of the session in YYYY-MM-DD format.| |
| start_time | The start time of the session in DATETIME (UTC) format. | |
| end_time | The end time of the session in DATEITIME (UTC) format. ||
| duration | The duration of the session in hours. |  |
| pre_reg_flag | A flag to indicate if a hands-on class requires pre-registration | Values are *TRUE* if pre-registration is required and *FALSE* if not. |
| paid_flag | A flag to indicate if a hands-on class requires payment to attend. | Values are *TRUE* if payment is required and *FALSE* if not. |
| laptop_flag | A flag to indicate if you need to take your own laptop to a hands-on class. | Values are *TRUE* if you need to bring your own laptop and *FALSE* if computers are provided (only for hands-on classes.) |
| speakers_cleaned | The name of the speaker and their affiliation. |  |
| session_type | The type of session at the conference. |Values include: Hands-on, Demo,  Panel, Common and Special |
| keywords | The keywords include topics for panel discussions as well as software used in the hands-on classes. |  |
| skill_level | The skill level of the session.| Values include Beginner, Intermediate, Advanced and General Interest |
