# cs2-log-channels
Dump of LoggingSystem_Log calls with arguments (including logging channel)

<b><code>LoggingSystem_Log(Networking, 2LL, "%s:  NetChan Setting Timeout to %4.2f seconds\n", v6, a3);</code></b>

1) arg1 - Log Channel
2) arg2 - Log Severity Level:
	LS_MESSAGE = 0,
	LS_WARNING = 1,
	LS_ASSERT = 2,
	LS_ERROR = 3,
  LS_HIGHEST_SEVERITY = 4, (Not a real severity value!)
3) arg3 - Log Message
