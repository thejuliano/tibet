# tibet

Intention is to create a distributed time-based event trigger service. Basically, one should be able to register a set event to be triggered at certain time, and this service will do a callback. 

Ideally, this project would be able to 

- provide ~100ms level precision on time.
- pseuo-horizontally scale. 
- support integration with most known messaging systems & databases. 
