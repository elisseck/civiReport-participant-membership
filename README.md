# civiReport-participant-membership
A custom civiCRM report based on an existing template. Joins the Membership table so membership information is available with participant reports

USE: Set you custom PHP and custom Template directories in civicrm admin
For example: /sites/default/files/civicrm/custom_templates
and /sites/default/files/civicrm/custom_php

Save your form php and template files mimicing the civiReport file structure, e.g.

*your custom php directory from above*/CRM/Report/Form/Event/ParticipantMemberships.php

and *your custom template directory from above*//CRM/Report/Form/Event/ParticipantMemberships.php

Register your report template in civiCRM report admin

Create new reports using the template!
