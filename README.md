<center> SUNBIRD INTERNATIONAL QUERIES.</center>


## What is Sunbird??

Sunbird is a societal learning platform built for cloud/mobile native environments and meant to address teaching and learning use cases.Multiple organizations can exist independently as tenants on the platform and users of these organizations can access the platform via mobile devices, laptops and desktops.

## Common Queries.

- Question:  Roles of content editor or content service (Content creator, reviewer etc.) and what actions those roles can do?

 <u>Answer</u>:    
            ### User Roles and Respective Responsibilities

|  User Role    | Content Creation | Review, Reject , & Publish | Upload Content | Other Actions |
|-------------------|---------------------|---------------------|-------------------------|-----------------|
| An **Organisation Administrator (Org admin)** manages the overall functioning and upkeep of the  organisation, and also define and manages user roles and permissions |       No       |       No       |  No | ✔️   <a href="features-documentation/#adminrole_matrix"> read more</a>
| A **System Administrator (Sys admin)** manages installation, configuration and operation of the system |       No       |       No       |  No | ✔️   <a href="features-documentation/#adminrole_matrix"> read more</a>
| A **Course Mentor** guides and instructs learners on how to undertake a course. They create batches of users to enrol for a course and ensure completion of a course within a stipulated time |       No       |       No       |  No | ✔️   <a href="features-documentation/userrole/#role-specific-responsibilites"> read more</a>~~       
| A **Content Reviewer** assesses  created content within prescribed guidelines | No | ✔️  | ✔️  | No 
| A **Teacher Badge Issuer** is responsible for assigning badges to teachers based on the discretion of the concerned organization | No | No | No | ✔️  <a href="features-documentation/userrole/#role-specific-responsibilites"> read more</a>
| A **Book Creator** curates and compiles books. Registered users become book creators when book creation rights are assigned to them | ✔️  (Only Books) | No | ✔️ | No 
|  A **Book Reviewer** assesses books within defined and prescribed guidelines| No | ✔️  (Only Books) | No | No
|A **Public** user is any user with registered credentials | No | No | No | ✔️  <a href="features-documentation/userrole/#role-specific-responsibilites"> read more</a>
| An **Announcement Sender** creates and sends announcements. The Announcement feature allows to send system wide messages to a target audience| No | No | No | ✔️  <a href="features-documentation/userrole/#role-specific-responsibilites"> read more</a>
| A **Content Creator** is a registered user with permission to create content | ✔️ (Collection, Course, Study Material, Lesson Plan) | No | ✔️ | No


- Question : Content publishing/workflow states???<br>
<u>Answer</u> : ```sequence
Draft->Review->Live/unlisted->flag(optional)```

- Question : Content authoring in collaboration. How it works? Can two users open the same content at the same time and edit?<br>
 <u>Answer</u> :  This Feature is still in devlopement Stage there is an Api call to Lock the content (params: userId,resourceId) and after making api call the content is locked for minimum 10 mins. and for content collaboration if two user(A,B) engaged in creating content then A will see his content in draft tab and B's content in collaboration tab.


<br/><br/>
- Question : Types of content supported<br/>
<u>Answer:</u>```
    Video (.mp4, .webm)
    HTML zip
    ECML (created using the inbuilt content editor)
    EPUB
    H5P
    Audio (.mp3)
    Images (.jpeg, .png)
    Document format (.pdf)
    URLs of YouTube videos and other files
    URLs of other externally hosted content. ```
