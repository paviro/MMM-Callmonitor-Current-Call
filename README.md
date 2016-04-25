# MMM-Callmonitor-Current-Call
This an extension for the [MagicMirror](https://github.com/MichMich/MagicMirror). It needs [MMM-FRITZ-Box-Callmonitor](https://github.com/paviro/MMM-FRITZ-Box-Callmonitor) and can display currently active calls.

## Installation
Navigate into your MagicMirror's `modules` folder and execute `git clone https://github.com/paviro/MMM-Callmonitor-Current-Call.git`.

## Usage
The entry in the `module array` in your `config.js` can look like the following.

```
{
	module: 'MMM-Callmonitor-Current-Call',
	position: "top_right",
	header: "Active Calls",
}
```

## Dependencies
- [MMM-FRITZ-Box-Callmonitor](https://github.com/paviro/MMM-FRITZ-Box-Callmonitor)





# MMM-Callmonitor-Current-Call
This an extension for the [MagicMirror](https://github.com/MichMich/MagicMirror) and can display currently active calls. It needs [MMM-FRITZ-Box-Callmonitor](https://github.com/paviro/MMM-FRITZ-Box-Callmonitor) or another module that can send <code>CALL_CONNECTED</code> and <code>CALL_DISCONNECTED</code> notifications.

## Installation
Navigate into your MagicMirror's `modules` folder and execute `git clone https://github.com/paviro/MMM-Callmonitor-Current-Call.git`.

## Using the module

To use this module, add it to the modules array in the `config/config.js` file:
````javascript
modules: [
	{
		module: 'MMM-Callmonitor-Current-Call',
		position: 'top_right',	// This can be any of the regions. Best results in left or right regions.
		header: "Active Calls", // This is optional
	}
]
````

## Dependencies
- [MMM-FRITZ-Box-Callmonitor](https://github.com/paviro/MMM-FRITZ-Box-Callmonitor)