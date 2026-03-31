# TheBaseTeam

![ICON$1](https://res.rsc-studio.com/projects/the-base-team/icons/1.png)

> Description \
> Name: TheBaseTeam \
> Author: RedStoneCity Studio \
> Least Version: 1.0-beta.1 (2026/3/31) \
> License: Apache 2.0

##### Copyright 2026 by [RedStoneCity Studio](https://www.rsc-studio.com)

## Description
> This is a chat framework software based on TCP technology with a management interface. Its drawback is that it's disposable; once the client is closed or the server is shut down, it cannot be recovered!

## How to use it
> For more, please link [RSC - Project Wiki](https://www.rsc-studio.com/project/wiki?projectname=thebaseteam)

### 1.Open install floder
Edit `config.json` file.
```json
{
  "AuthProject": "TheBaseTeam",
  "WebDashboard": {
    "RouterUrl": "127.0.0.1",
    "RouterPort": "2550",
    "Path": "website"
  }
}
```

### 2.Restart computer, Finish the server client.
Start `http://127.0.0.1:2550` \
Click `Language`, and change your language.

#### Start server
Start `Server` options.
Click `Add new server`, configure the server as prompted.
> [NOTICE] If you need to connect across different Wi-Fi networks, configure a network tunneling software; Cpolar is recommended.

Click `Start this server`.

### Join server
Enter `127.0.0.1:<Server Port>` or public URL\
#### Join success
Enter your message, boardcast your message.
#### Position in queue
The server may be trying to reduce memory usage; the rooms are full, and you'll need to wait in line for a while.
