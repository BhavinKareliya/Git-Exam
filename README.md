# Git-Exam

### Practical-1: Pull and Merge difference 

Step-1: Add feature-1 & feature-2 and push to feature branch
![add_feat1_feat2](https://user-images.githubusercontent.com/124888034/221111927-0c4303d6-312a-4b28-b44a-44d0e02517e4.png)
|------------------------------------------------------------------------------------------------------------------------|

Step-2: Create PR and merge into main branch
![merged_feat](https://user-images.githubusercontent.com/124888034/221112260-a4f5912b-5bab-4940-86e1-63514142c3d8.png)
|--------------------------------------------------------------------------------------------------------------------|

---

### Practical-2: Rebase
*pull commit from feature branch to main without merge into single commit using rebase
![rebase](https://user-images.githubusercontent.com/124888034/221112958-52ce3f34-0aec-4373-94f5-2cc6b366d40e.png)
|---------------------------------------------------------------------------------------------------------------|

---

### Practical-3: Change commit message

Step-1: create and push the commit in feature branch
![1_change_git_message](https://user-images.githubusercontent.com/124888034/221112917-ce39e34d-5eee-4795-8a98-7d962c14a4e6.png)
|-----------------------------------------------------------------------------------------------------------------------------|

![2_before_change_message](https://user-images.githubusercontent.com/124888034/221112923-d1bf6b73-0704-4bc1-9b5e-caa1bd658aec.png)
|--------------------------------------------------------------------------------------------------------------------------------|

Step-2: Apply reword action for change commit message
![3_rebase_todo](https://user-images.githubusercontent.com/124888034/221112935-9f06992e-a1d8-49a4-b825-aa83365412b2.png)
|----------------------------------------------------------------------------------------------------------------------|

Step-3: Change commit message and push back to remote
![4_rebase](https://user-images.githubusercontent.com/124888034/221112939-0470cf46-b436-4e3d-a060-328fe86fb247.png)
|-----------------------------------------------------------------------------------------------------------------|

Step-4: changed commit message
![5_after_change_commit](https://user-images.githubusercontent.com/124888034/221112940-dba6b243-5e8b-499e-b462-5627b1828122.png)
|------------------------------------------------------------------------------------------------------------------------------|

---

### Practical-4: cherry pick
**Used cherry-pick command to merge only selected commits using their commit_ID
![cherry-pick](https://user-images.githubusercontent.com/124888034/221112953-165570e2-7ff2-4d0c-9d6d-e0f18a7feeb6.png)
|--------------------------------------------------------------------------------------------------------------------|

---

### Practical-5: Drop commit

Step-1: Before drop (For example,Here I mistaken commited "Feature-7" into main as shown in below image and I have to drop that from main)
![2_drop_commit](https://user-images.githubusercontent.com/124888034/221112930-5869751e-9a95-4587-ac63-8553a105bd16.png)
|----------------------------------------------------------------------------------------------------------------------|

Step-2: Used rebase and select postion of that commit from HEAD and apply drop action
![3_drop_commit](https://user-images.githubusercontent.com/124888034/221112934-3101e1be-917a-4233-bf86-582d0f300808.png)
|----------------------------------------------------------------------------------------------------------------------|

Step-3: after drop the commit
![5_after_drop_commit](https://user-images.githubusercontent.com/124888034/221112943-653004fc-239b-4d31-9690-da1880554c5a.png)
|----------------------------------------------------------------------------------------------------------------------------|
