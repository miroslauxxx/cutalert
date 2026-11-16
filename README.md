### playbook to trigger cute informative alert with Max from 42 berlin using `zed`
Un or fortunately I've not found proper solution with module, latest version written as shell command, but it's more beautiful than with module.

example usage with default max image:
ansible-playbook -i localhost playbook.yaml -e "title='❤<fe0f> MAX NOTIFYING \!\!\!❤<fe0f>'" -e  "message='COMMUNITY MEETING HAPPENS IN 5 MINS IN AUDITORIUM'"

example usage without your image:
ansible-playbook -i localhost playbook.yaml -e "image=/path/to/your/cute/cat" -e "title='❤<fe0f> MAX NOTIFYING \!\!\!❤<fe0f>'" -e  "message='COMMUNITY MEETING HAPPENS IN 5 MINS IN AUDITORIUM'"

_with love by @milnicki_
