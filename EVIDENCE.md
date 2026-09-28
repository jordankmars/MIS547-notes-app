See `./action-screenshot.png` and `./docker-tags-screenshot.png`

## Experiment 2 Output

```bash
[{"body":"hello from kubernetes","created_at":"2026-09-28T05:22:09.413675+00:00","id":1},{"body":"I should survive a pod deletion","created_at":"2026-09-28T05:23:23.855651+00:00","id":2}]
```

## Experiment 3 Output

```bash
{"message":"Hello there from the notes app!!!","served_by":"web-55b7b65f8b-x99wc","service":"notes-app"}

{"message":"Hello there from the notes app!!!","served_by":"web-55b7b65f8b-x99wc","service":"notes-app"}

{"message":"Hello there from the notes app!!!","served_by":"web-55b7b65f8b-x99wc","service":"notes-app"}

All commands and output from this session will be recorded in container logs, including credentials and sensitive information passed through the command prompt.
If you don't see a command prompt, try pressing enter.
Session ended, resume using 'kubectl attach curl -c curl -n notes-lab -i -t' command
pod "curl" deleted from notes-lab namespace
```

## Rolling Update History Output

```bash
deployment.apps/web
REVISION CHANGE-CAUSE
1 <none>
2 <none>
3 <none>
```
