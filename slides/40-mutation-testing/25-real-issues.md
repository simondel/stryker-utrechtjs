### Real issues

```gherkin
Given team member is allowed to assign the role 'Reader'
When the team member adds the following member to the team
| field     | value                  |
| Username  | HarryJ				 |
| Role      | Administrator          |
Then the team member should see the error 'Forbidden'
```

Note:
Talk about case where this test passed even though the implementation was incorrect due to the fact that a stub was used in the implementation of this spec.