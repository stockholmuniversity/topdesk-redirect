# TOPdesk redirector

Use a bookmark with a keyword to open a ticket number in TOPdesk via this
application which finds out the `unid` of the ticket to be able to redirect you
to the correct ticket.

# Usage

Of course, install and use this application inside a venv or container.

## Installation
```shell
$ pip3 install topdesk-redirect
```

## Running

### Using `flask run`
```shell
$ FLASK_APP=topdesk_redirect:app flask run
```

### In prod using e.g. `gunicorn`
```shell
$ pip3 install gunicorn
$ gunicorn topdesk_redirect:app
```
