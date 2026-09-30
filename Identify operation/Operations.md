Identify Operations
Smart Museum Artifact Conservation System
OP_ID 	Operation                     	Purpose
OP01	Perform Self-Check   	          Test all essential sensors and environmental-control devices at power-on so the chamber never runs with faulty hardware.
OP02	Enter Monitoring                Mode	Move the chamber into MONITORING mode once the self-check succeeds.
OP03	Register Artifact	              Record the artifact's identification information when it is placed inside the chamber.
OP04	Load Environmental Profile	    Load the artifact's required temperature and humidity limits so they can be used for comparison.
OP05	Monitor Sensors Continuously	  Continuously read temperature, humidity, light, vibration, door status, artifact condition and power availability.
OP06	Check Door Status	              Confirm the chamber door is closed before active conservation can begin.
OP07	Activate Conservation	          Enter CONSERVATION_ACTIVE mode when the door is closed and the artifact profile is loaded.
OP08	Compare Readings with Limits	  Compare actual temperature and humidity with the artifact's permitted ranges to detect deviations.
OP09	Correct Temperature	            Issue a correction command to restore temperature to the permitted range.
OP10	Correct Humidity	              Issue a correction command to restore humidity to the permitted range.
OP11	Verify Recovery	                Confirm through sensor readings (not just the command) that the condition is back in range within the recovery period.
OP12	Enter Protection Mode	          Switch to PROTECTION_MODE when a condition cannot be corrected within the allowed recovery period.
