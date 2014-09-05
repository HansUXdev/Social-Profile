> < team-block > is custom element designed to make it faster to build professional about pages featuring a companies team.


## File Structure

Versions                    | Details                                                   |                         
---                         | ---                                                       |    
-- `index.html`             | Self explanatory                                          |                        
-- `_team-var.scss`         | Used to make quick changes to the element(s).             |                
---`src`                    | MAIN folder.                                              |                          
---->`ideal-type.html`      | Used to outline/brain storm how markup should look in lightDom and ShadowDOM |  
---->`team-profile.html`    | Used for version 1 & 2. Then refactored into team-member. |   
---->`team-member.html`     | Individual member block.                                  |  
---->`team-block.html`      | Imports above element and repeats according to team.json. |  
---->`team-service.html`    | Used to call ajax and the api.                            |
---->`api`                  | Folder containing your .json files.                       |
------>`team.json-`         | Define.                                                   |



## Road Map

Versions        | Details                                                   | T0-DO                         | Status
---             | ---                                                       | ---                           | ---
`Version 1`     | Will be built in with vanilla HTML then refactored.       | `refactor sass`               | Started
`Version 2`     | Will be a working concept with four members.              | `32`                          | Started
`Version 3`     | Will START implimenting templating and customization      | 'team.json', 'team-services', | Started
`Version 4`     | Will be the completed version.                            | - Merge with master           | Incomplete

## Elements

Element         | Attributes                                              | Options                             
---             | ---                                                     | ---                                 
`team-block`    | `type`                                                  | `hover-icon`, `hover-description`   
`team-member`   | -                                                       | -                                
                               




## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

