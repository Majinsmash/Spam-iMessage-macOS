# Spam iMessage (macOS)
Spam iMessage via Automator on macOS

## How to use
When you first open the workflow, you will be greeted by this code:
```
tell application "Messages"
	
	send "{{MESSAGE}}" to buddy "{{PHONE NUMBER}}" of (service 1 whose service type is iMessage)
	
end tell
```

### Edit Message
Replace `{{MESSAGE}}` with whatever you wish to spam

### Edit Phone Number
Replace `{{PHONE NUMBER}}` with a phone number. Rather than formatting the number as something like `+1(234)567-8910`, you'd instead format it as `+12345678910`.

### Change How Many Times Its Spammed
This step is really easy. All you need to do is find the text input in the Loop object, and replace it with however many times you want to spam the message
