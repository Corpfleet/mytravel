# Corpfleet Mytravel
## Changelog

### **v1.1 to be released**
- load routes from backend (CTRL+SHIFT+, to force backend reload update)
- ability to update Takeflite routes
- next/previous day on select flight pag
- terms and conditions
- aesthetic changes:
   - from and to text on confirmation page
   - _back button_
   - sign out button on confirmation screen
   - hide fares when less than 1 NGN 

### **v1.0 "MVP" - 21 July 2021**
##### Basic functionality:
- Flight and boat booking through apis
- Guesthouse booking
- Pickup/Dropoff booking
- _Routes are hardcoded_

---  

## To-do list:  
* Don't allow booking same type twice (i.e. 1 flight, 1 guesthouse, 1 pickup/drop-off)
* Ability to update Takeflite routes
* Pick-up/ drop-off required after flight/boat booking
* Display correct transportation mode icon on upcoming trips screen (combine GDS and local data)
* Accept terms and conditions
* Payment gateway
* Guesthouse multiple locations (e.g. Bonny and Port Harcourt)
* Feedback
* Hide fares when less than 1 NGN 
* Don't send fares to Cytric when less than 1 NGN (backend)
* Sign out button on confirmation screen
* Pre populate departure/arrival dates after first booking
* Elina guesthouse allowed per Location ID (backend - company rules)
* Elina book multiple rooms when no of pax more than allowed room occupancy (backend)
* Company rules service
* Routing/Availability service - controlled in N-Logistics

| Location      | Pickup/Dropoff  | 
| ------------- |:--------------| 
| Port Harcourt | Office        | 
|               | Hotel         |  
|               |               |  
| Bonny         | Home          |   
|               | Office        |   
|               | Guesthouse    |  

