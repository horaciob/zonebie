## 0.5 (15 August 2013)

* Changed the environment variable used to make tests temporarily deterministic
  from `TZ` to `ZONEBIE_TZ`. `TZ` has meaning to the system and so it was not
  appropriate for Zonebie to use it. (Andy Lindeman)
* Removed support for displaying an ASCII map. It added too many weird
  dependencies to the gem. (Andy Lindeman)