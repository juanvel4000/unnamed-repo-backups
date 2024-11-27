# unnamed-repo-backups

```
                                  welcome to                           __                                                 
                                                                      |  \                                                
 __    __  _______   _______    ______   ______ ____    ______    ____| $$          ______    ______    ______    ______  
|  \  |  \|       \ |       \  |      \ |      \    \  /      \  /      $$ ______  /      \  /      \  /      \  /      \ 
| $$  | $$| $$$$$$$\| $$$$$$$\  \$$$$$$\| $$$$$$\$$$$\|  $$$$$$\|  $$$$$$$|      \|  $$$$$$\|  $$$$$$\|  $$$$$$\|  $$$$$$\
| $$  | $$| $$  | $$| $$  | $$ /      $$| $$ | $$ | $$| $$    $$| $$  | $$ \$$$$$$| $$   \$$| $$    $$| $$  | $$| $$  | $$
| $$__/ $$| $$  | $$| $$  | $$|  $$$$$$$| $$ | $$ | $$| $$$$$$$$| $$__| $$        | $$      | $$$$$$$$| $$__/ $$| $$__/ $$
 \$$    $$| $$  | $$| $$  | $$ \$$    $$| $$ | $$ | $$ \$$     \ \$$    $$        | $$       \$$     \| $$    $$ \$$    $$
  \$$$$$$  \$$   \$$ \$$   \$$  \$$$$$$$ \$$  \$$  \$$  \$$$$$$$  \$$$$$$$         \$$        \$$$$$$$| $$$$$$$   \$$$$$$ 
                                                                                                      | $$                
                                                                                                      | $$                
                                                                                                       \$$                
 __                            __                                                                                         
|  \                          |  \                                                                                        
| $$____    ______    _______ | $$   __  __    __   ______    _______                                                     
| $$    \  |      \  /       \| $$  /  \|  \  |  \ /      \  /       \                                                    
| $$$$$$$\  \$$$$$$\|  $$$$$$$| $$_/  $$| $$  | $$|  $$$$$$\|  $$$$$$$                                                    
| $$  | $$ /      $$| $$      | $$   $$ | $$  | $$| $$  | $$ \$$    \                                                     
| $$__/ $$|  $$$$$$$| $$_____ | $$$$$$\ | $$__/ $$| $$__/ $$ _\$$$$$$\                                                    
| $$    $$ \$$    $$ \$$     \| $$  \$$\ \$$    $$| $$    $$|       $$                                                    
 \$$$$$$$   \$$$$$$$  \$$$$$$$ \$$   \$$  \$$$$$$ | $$$$$$$  \$$$$$$$                                                     
                                                  | $$                                                                    
                                                  | $$                                                                    
                                                   \$$                                                                    

```
This Repository contains snapshots of unnamed-repo, everytime the repo is built, a snapshot may be uploaded here
## Compression
Snapshots are compressed using .tar.zst `tar -cf - * | zstd -o`
MIN:HOUR-DAY-MONTH-YEAR
or
`$(date "+%M:%H-%d-%m-%Y"`
## How is this made
unnamed-repo has a script that compiles the packages, uploads those to the repository and if choosen to, the previous build of unnamed-repo is compressed and if marked as so, uploaded to this repository
