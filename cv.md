# Ivan Kuliashov
___
## E-mail: dfyreybr@gmail.com
## +375 (29) 513-23-02
### Links to social networks: [VK](https://vk.com/ivan.kuleshov19) [Git](https://github.com/Krivetka)
>Measuring programming progress by lines of code is like measuring aircraft building progress by weight.
#### Strengths:
* Creative abilities
* Logical thinking
* Industriousness
* Responsibility 
* A quick learner
#### I know :
* C++
* Python 
* HTML
* CSS
* SQL
#### Used in projects
* Bootstrap
* Yii

javascript
    function displayMessages() {
             let displayMessage =``;
             todoList.forEach(function (item, i){
                 displayMessage += 
                 <li class="list-group-item d-flex w-100 mb-2" style="background:${item.color}">
                     <div class="w-100 mr-2">
                         <div class="d-flex w-100 justify-content-between">
                             <h5 class="mb-1" for="item_${i}">${item.title}</h5>
                                 <div>
                                     <small class="mr-2" >${item.important}</small>
                                     <small >${item.data}</small>
                                </div>
                                 </div>
                                 <p class="mb-1 w-100"  id="item_${i}">${item.text}</p>
                             </div>
                             <div class="dropdown m-2 dropleft">
                                 <button class="btn btn-secondary h-100" type="button" id="dropdownMenuItem1" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                     <i class="fas fa-ellipsis-v"></i>
                                 </button>
                                 <div class="dropdown-menu p-2 flex-column" aria-labelledby="dropdownMenuItem1">
                                     <button type="button" class="btn btn-success w-100"  id="complete_${i}">Complete</button>
                                     <button type="button" class="btn btn-info w-100 my-2"  id="edit_${i}">Edit</button>
                                     <button type="button" class="btn btn-danger w-100"   id="delete_${i}"}>Delete</button>
                                 </div>
                             </div>
                         </li>
                 ;
                 todo.innerHTML=displayMessage;
             });
         }
