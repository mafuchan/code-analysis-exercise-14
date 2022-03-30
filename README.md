# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}


```

Inputs and outputs should be valid JavaScript values!

| Input   | Output  |
| -----   | ------  |
| {username: "user1", isActive: true}  |  `Welcome back, user1!`  | 
| {username: "user2", isActive: false} | `Hey user2! Would you like to renew your subscription?` | 
| {username: "user3", isActive: true}  |  `Welcome back, user3!`  | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>The input of user and status is entered in. If the user name is active(true), it returns the message 'Welcome back, user1!' If the user is not active(false) it returns the message of 'Hey user2! Would you like to renew your subscription?'</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
