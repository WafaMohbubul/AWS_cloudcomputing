## What is PM2?

#### WHat is PM2?
-  advanced process manager for NodeJS applications
- comes with a built-in load balancer.
- allows you quickly start, control, or stop your node processes
- runs as a daemon on the server 

### Why is it useful?
- helps facilitate production deployments 
- enables you to keep running applications alive indefinitely
- lets you gain insights into your application's runtime performance and resource consumption
- lets you scale your application in real-time through its clustering feature.

### Useful PM2 commands
- Start and name a process: `pm2 start app.js --name my-api` 
- Will start maximum processes with LB depending on available CPUs: `Will start maximum processes with LB depending on available CPUs`
- Display all process status: `pm2 list`
- Display json process list: `pm2 jlist`

#### Actions
- Stop all processes: `pm2 stop all`
- Restart all processes: `pm2 restart all`
- Stop specific process ID: `pm2 stop 0`
- Will remove all processes from pm2 list: `pm2 delete all`
- 
#### Logs
- Display all processes logs in streaming: `pm2 logs [--raw]`
- Empty all log files: `pm2 flush`
- Reload all logs: `pm2 reloadLogs`
- Will 0s downtime reload (for NETWORKED apps): `pm2 reload all`

Source: https://devhints.io/pm2

