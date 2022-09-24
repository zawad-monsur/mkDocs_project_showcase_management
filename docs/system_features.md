# System Features

###### Login/Signup and Dashboard

<dl>
    <dt>Description and Priority:</dt>
    Students,faculty and organizers have different login sections and authentication checks from the database and both have different dashboards. This is the high priority feature of this project.
</dl>

<dl>
    <dt>Stimulus/Response Sequences:</dt>

    Student faculty and organizers must login by using there’re id and password. After login every side has a different dashboard and there, they can upload projects, observe projects and organizers add judges and create notices..
</dl>

<dl>
    <dt>Functional Requirements:</dt>
    Students, faculty and organizers have different login requirements like id and password to access this software. If they failed to login then they have to sign up first and get an authentication check from the organization.
</dl>
    REQ-1: Students should have to Login	
    REQ-2:Organizers assign the judges
    REQ-3:Faculty should have unique id and password

###### Create a Project

Students have to create their own project after team formation . They have to put their details       and Project ideas with a short description. Without creating a project there would be no project record against the team.

<dl>
    <dt>Stimulus/Response Sequences:</dt>

    Students have to perform an add project and create a project with the form’s requirements. After creating the project they will be able to see the project idea feedback complimented by the course teacher.
</dl>

<dl>
    <dt>Functional Requirements:</dt>
    As a user only student can create a project according to course category with information like team members id, project title, project idea,project description and other stuff with specific format that requires to be stored in the database as the format.
</dl>
    REQ-1: Students should have to create profile
    REQ-2:Students have to create team must.
    REQ-3: Student have to maintain form’s Format

###### Project Evaluation

After students submit their project, judges might evaluate every project based on their project performance and judges might give marks to every portion of the project.After evaluate judges upload their marks.

<dl>
    <dt>Stimulus/Response Sequences:</dt>

    Project evaluation where judges can see all the projects individually and evaluate projects and also assign marks for the project..
</dl>

<dl>
    <dt>Functional Requirements:</dt>
    After students submit their project judges might evaluate every project based on their project performance and judges might give marks to every portion of the project.After evaluate judges upload their marks .If the judges can't properly evaluate update marks then every project marks upload in the marks history database.
</dl>
    REQ-1: Views student projects file
    REQ-2: Access to see every portion of project


###### Notice Board

 Organizers can upload the notice and  students and faculty can view the notice from the notice board.

<dl>
    <dt>Stimulus/Response Sequences:</dt>

    When organizers upload a notice, students and faculty can view the notice.
</dl>

<dl>
    <dt>Functional Requirements:</dt>

    After upload notice from organizers the can edit delete and upload the notice
</dl>
    REQ-1: Student view notice
    REQ-2:  Organizers have access to edit delete of notice.


###### Create team & Team Enrollment 

Students have to create their own project after team formation . They have to put their details       and Project ideas with a short description. Without creating a project there would be no project record against the team.

<dl>
    <dt>Stimulus/Response Sequences:</dt>

    Students have to perform an add project and create a project with the form’s requirements. After creating the project they will be able to see the project idea feedback complimented by the course teacher.
</dl>

<dl>
    <dt>Functional Requirements:</dt>
    As a user only student can create a project according to course category with information like team members id, project title, project idea,project description and other stuff with specific format that requires to be stored in the database as the format.
</dl>
    REQ-1: Students should have to create profile
    REQ-2:Students have to create team must.
    REQ-3: Student have to maintain form’s Format

###### Submit project & Add project updates

After creating teams, students submit their projects and faculty will monitor and students can add project updates every sprint.

<dl>
    <dt>Stimulus/Response Sequences:</dt>

    students upload project and sumit then the can add project updates every time.Feculty have access to see the project update
</dl>

<dl>
    <dt>Functional Requirements:</dt>
    After students submit their project, faculty can access the project progress.
</dl>
    REQ-1: Views student projects file
    REQ-2: Access to see every portion of project


###### Project Search

Students and faculties can search projects and search result will show the previous projects done before.

<dl>
    <dt>Stimulus/Response Sequences:</dt>

    Students upload project and sumit then the can add project updates every time.Feculty have access to see the project update
</dl>

<dl>
    <dt>Functional Requirements:</dt>
    After student search they will get previous history of project if any project have same name then that will may conflict so we use unique project id of every project
</dl>
    REQ-1: search the previous project
    REQ-2: Access to see history of previous course project