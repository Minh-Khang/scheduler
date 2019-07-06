# Scheduler

Users 		  -> Email, Name, Password 		     -> Has many Companies -> Has many Shifts
Companies 	-> User, Schedule 				       -> Has many Users -> Has one Schedule
Shift 		  -> User, Start Time, End Time 	 -> Attached to one person -> Attached to one schedule
Schedule 		-> Name, Shift 				           -> Has many Shifts
