# Znuny Multiple Tab Agent Ticket Status View 
- display multiple tab of agent ticket status filtered by ticket type (opens ticket).
- based file Znuny 7.0.9
- you may later need to update / patch it based on latest release of znuny (refer no 3).

1. Deploy the files to their location, set the correct permissions and deploy config.

2. Update the correct Ticket Type to be filter at Admin > Ticket::Frontend::AgentTicketStatusView###ViewBy::Type

	Example
	
		1 => Problem
		2 => Incident
		
		*where 1 = order of the field,
		*where Problem = ticket type name,
		
		*where 2 = order of the field,
		*where Incident = ticket type name,

3. Additional code has been tagged with

		# --
		# Agent Ticket Status View by Ticket Type Tab
		# --
		CODE CODE CODE
		# --
		
	
![ticket-status-setting](status_view_config.png)

![ticket-status-screen](status_view_screen.png)
