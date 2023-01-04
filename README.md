# slack-notify

### Inputs:

| Name  | Required | Details | Default value |
| :---: | :------: | :-----: | :-----------: |
| message-type | yes | [`start`, `results`] | |
| slack-channel | yes | | |
| slack-bot-token | yes | | |
| message-ts | no | | |
| steps-context | no | | |

<br>

### Outputs:

- **message-ts**: Timestamp of the message sent to the channel (only with `message-type == start`)
