<!DOCTYPE html>
<!-- saved from url=(0041)https://alx-intranet.hbtn.io/projects/564 -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <meta name="description" content="">
    <meta name="google" content="notranslate">

    <title>Project: Build your portfolio project (Week 2): MVP Complete | ALX Africa Intranet</title>

      <link rel="stylesheet" href="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/xgz4ilr.css">
      <link rel="stylesheet" media="all" href="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/application_alx-797565f98971caf22e304b8614ecbc3b779f242f268834e9b46baa0f0eab4c36.css">
      <script async="" src="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/analytics.js"></script><script src="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/loader.js"></script>
      <script src="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/application-fbcf5ccea5ceafdf088aa0038b1711206df04afdbfaa68fdac52645a6794d031.js"></script>
      <link rel="shortcut icon" type="image/x-icon" href="https://alx-intranet.hbtn.io/favicon_alx.ico">
      <meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="ZLNmKDUgkkkuP4sw/NY1IlMEN3q+sK1Sw90BZXJ+DOWBIb2g5S+VlHZahz+B1nN4Qo+RU+9e1BTEH7XY/aPLfQ==">

      <link rel="apple-touch-icon" href="https://alx-intranet.hbtn.io/apple-touch-icon_alx.png">

      <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
      <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
        <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <![endif]-->

      <!-- Store user timezone -->
      <script>
        Cookies.set('timezone', (new Date()).getTimezoneOffset() / -60.0);
      </script>

      <!-- intro.js for interactive onboarding -->

      <!-- React -->
      <script src="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/application-8906ffaaef5d4eccdf0b.js"></script>
      <link rel="stylesheet" media="screen" href="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/application-f61adf9f.css">

  </head>

  <body class="
    signed_in
    env_production
    
    " translate="no" data-theme-suffix="_alx" data-checker-special-theme="">

      <input type="hidden" id="hbtn-slack-url" value="https://alx-students.slack.com">
      <nav class="navbar navbar-default navbar-fixed-top topbar visible-xs">
  <div class="navbar-header">
    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-mobile" aria-expanded="false">
      <span class="sr-only">Toggle navigation</span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
      <span class="icon-bar"></span>
    </button>

    <a class="navbar-brand" href="https://alx-intranet.hbtn.io/">
      <div class="logo"></div>
</a>  </div>

  <div class="collapse navbar-collapse navigation" id="navbar-mobile">
    <ul class="nav navbar-nav">
      


    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Planning"><a href="https://alx-intranet.hbtn.io/dashboards/my_planning"><div class="icon "><i aria-hidden="true" class="fa fa-calendar "></i></div><div class="visible-xs">Planning</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-current-projects-item" title="" data-original-title="Projects"><a href="https://alx-intranet.hbtn.io/projects/current"><div class="icon "><i aria-hidden="true" class="fa fa-code-fork "></i></div><div class="visible-xs">Projects</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My reports"><a href="https://alx-intranet.hbtn.io/users/my_reports"><div class="icon "><i aria-hidden="true" class="fa fa-sticky-note-o "></i></div><div class="visible-xs">My reports</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="QA Reviews I can make"><a href="https://alx-intranet.hbtn.io/corrections/to_review"><div class="icon "><i aria-hidden="true" class="fa fa-check "></i></div><div class="visible-xs">QA Reviews I can make</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Evaluation quizzes"><a href="https://alx-intranet.hbtn.io/dashboards/my_current_evaluation_quizzes"><div class="icon "><i aria-hidden="true" class="fa fa-question "></i></div><div class="visible-xs">Evaluation quizzes</div></a></li>

    <hr title="My resources">

    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Curriculums"><a href="https://alx-intranet.hbtn.io/dashboards/my_curriculums"><div class="icon "><i aria-hidden="true" class="fa fa-graduation-cap "></i></div><div class="visible-xs">Curriculums</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-concepts-item" title="" data-original-title="Concepts"><a href="https://alx-intranet.hbtn.io/concepts"><div class="icon "><i aria-hidden="true" class="fa fa-file-text "></i></div><div class="visible-xs">Concepts</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-video-rooms" title="" data-original-title="Conference rooms"><a href="https://alx-intranet.hbtn.io/dashboards/video_rooms"><div class="icon "><i aria-hidden="true" class="fa fa-comments "></i></div><div class="visible-xs">Conference rooms</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Servers"><a href="https://alx-intranet.hbtn.io/servers"><div class="icon "><i aria-hidden="true" class="fa fa-server "></i></div><div class="visible-xs">Servers</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-my-containers" title="" data-original-title="Sandboxes"><a href="https://alx-intranet.hbtn.io/user_containers/current"><div class="icon "><i aria-hidden="true" class="fa fa-terminal "></i></div><div class="visible-xs">Sandboxes</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Tools"><a href="https://alx-intranet.hbtn.io/dashboards/my_tools"><div class="icon "><i aria-hidden="true" class="fa fa-wrench "></i></div><div class="visible-xs">Tools</div></a></li>
    

      <hr title="My campus">

      
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Peers"><a href="https://alx-intranet.hbtn.io/users/peers"><div class="icon "><i aria-hidden="true" class="fa fa-users "></i></div><div class="visible-xs">Peers</div></a></li>
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Captain&#39;s Logs"><a href="https://alx-intranet.hbtn.io/dashboards/my_captain_log"><div class="icon "><i aria-hidden="true" class="fa fa-book "></i></div><div class="visible-xs">Captain's Logs</div></a></li>
      
      


<hr class="visible-xs">

<li>
    <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Slack">
      <a target="_blank" href="https://alx-students.slack.com/">
        <div class="image slack">
          <div class="inner"></div>
        </div>
        <div class="visible-xs">Slack</div>
</a>    </div>

  <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My Profile">
    <a href="https://alx-intranet.hbtn.io/users/my_profile">
        <div class="image ">
          <div class="inner" style="background-image: url(&#39;https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/000/850/thumb/IMG_20190729_142005.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220422%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220422T220732Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=839da3c2b3febdeaf7caef4e022162584681deb22be7653b3c17f9509ab92125&#39;)"></div>
        </div>

      <div class="visible-xs">My Profile</div>
</a>  </div>
</li>


    </ul>
  </div>
</nav>

      <div class="hidden-xs navigation sidebar">
  <a class="logo-container" href="https://alx-intranet.hbtn.io/">
    <div class="logo"></div>
</a>
  <ul>
    


    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Planning"><a href="https://alx-intranet.hbtn.io/dashboards/my_planning"><div class="icon "><i aria-hidden="true" class="fa fa-calendar "></i></div><div class="visible-xs">Planning</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-current-projects-item" title="" data-original-title="Projects"><a href="https://alx-intranet.hbtn.io/projects/current"><div class="icon "><i aria-hidden="true" class="fa fa-code-fork "></i></div><div class="visible-xs">Projects</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My reports"><a href="https://alx-intranet.hbtn.io/users/my_reports"><div class="icon "><i aria-hidden="true" class="fa fa-sticky-note-o "></i></div><div class="visible-xs">My reports</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="QA Reviews I can make"><a href="https://alx-intranet.hbtn.io/corrections/to_review"><div class="icon "><i aria-hidden="true" class="fa fa-check "></i></div><div class="visible-xs">QA Reviews I can make</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Evaluation quizzes"><a href="https://alx-intranet.hbtn.io/dashboards/my_current_evaluation_quizzes"><div class="icon "><i aria-hidden="true" class="fa fa-question "></i></div><div class="visible-xs">Evaluation quizzes</div></a></li>

    <hr title="My resources">

    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Curriculums"><a href="https://alx-intranet.hbtn.io/dashboards/my_curriculums"><div class="icon "><i aria-hidden="true" class="fa fa-graduation-cap "></i></div><div class="visible-xs">Curriculums</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-concepts-item" title="" data-original-title="Concepts"><a href="https://alx-intranet.hbtn.io/concepts"><div class="icon "><i aria-hidden="true" class="fa fa-file-text "></i></div><div class="visible-xs">Concepts</div></a></li>
    
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-video-rooms" title="" data-original-title="Conference rooms"><a href="https://alx-intranet.hbtn.io/dashboards/video_rooms"><div class="icon "><i aria-hidden="true" class="fa fa-comments "></i></div><div class="visible-xs">Conference rooms</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Servers"><a href="https://alx-intranet.hbtn.io/servers"><div class="icon "><i aria-hidden="true" class="fa fa-server "></i></div><div class="visible-xs">Servers</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" id="sidebar-dashboards-my-containers" title="" data-original-title="Sandboxes"><a href="https://alx-intranet.hbtn.io/user_containers/current"><div class="icon "><i aria-hidden="true" class="fa fa-terminal "></i></div><div class="visible-xs">Sandboxes</div></a></li>
    <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Tools"><a href="https://alx-intranet.hbtn.io/dashboards/my_tools"><div class="icon "><i aria-hidden="true" class="fa fa-wrench "></i></div><div class="visible-xs">Tools</div></a></li>
    

      <hr title="My campus">

      
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Peers"><a href="https://alx-intranet.hbtn.io/users/peers"><div class="icon "><i aria-hidden="true" class="fa fa-users "></i></div><div class="visible-xs">Peers</div></a></li>
      <li data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Captain&#39;s Logs"><a href="https://alx-intranet.hbtn.io/dashboards/my_captain_log"><div class="icon "><i aria-hidden="true" class="fa fa-book "></i></div><div class="visible-xs">Captain's Logs</div></a></li>
      
      


<hr class="visible-xs">

<li>
    <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="Slack">
      <a target="_blank" href="https://alx-students.slack.com/">
        <div class="image slack">
          <div class="inner"></div>
        </div>
        <div class="visible-xs">Slack</div>
</a>    </div>

  <div data-container="body" data-placement="right" data-toggle="tooltip" title="" data-original-title="My Profile">
    <a href="https://alx-intranet.hbtn.io/users/my_profile">
        <div class="image ">
          <div class="inner" style="background-image: url(&#39;https://s3.amazonaws.com/alx-intranet.hbtn.io/users/photos/000/000/850/thumb/IMG_20190729_142005.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220422%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20220422T220732Z&amp;X-Amz-Expires=600&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=839da3c2b3febdeaf7caef4e022162584681deb22be7653b3c17f9509ab92125&#39;)"></div>
        </div>

      <div class="visible-xs">My Profile</div>
</a>  </div>
</li>


  </ul>
</div>


    <main>
      <div id="layout-bars">
        

        

        

        
      </div>

      <article class="">

        
<div class="project row">
  <div class="col-xs-12 col-md-10 col-lg-8 contains-images">

      <h1 class="gap">Build your portfolio project (Week 2): MVP Complete</h1>

  <div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[]}" data-react-cache-id="tags/Tags-0"></div>

  <ul class="list-group metadata" id="project-metadata">

    <li class="list-group-item">
      <i aria-hidden="true" class="fa fa-user  fa-fw"></i>
      By Staff
    </li>

    <li class="list-group-item">
      <i aria-hidden="true" class="fa fa-cogs  fa-fw"></i>
      Weight: 3
    </li>


    <li class="list-group-item">
      <i aria-hidden="true" class="fa fa-users  fa-fw"></i>
      Project to be done in teams of 3 people
        (your team: Elijah Daniel, Njagi Ndungo, Edafe Oke
    </li>

      <li class="list-group-item">
        <i aria-hidden="true" class="fa fa-calendar  fa-fw"></i>
          Project over - took place from <div data-react-class="common/DateTime" data-react-props="{&quot;showDate&quot;:true,&quot;showTime&quot;:false,&quot;value&quot;:&quot;2022-03-04T06:00:00.000+03:00&quot;}" data-react-cache-id="common/DateTime-0" class="d-inline-block"><span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2022-03-04 04:00 (GMT+01:00)"><span class="datetime">Mar 4, 2022 </span></span></div> to <div data-react-class="common/DateTime" data-react-props="{&quot;showDate&quot;:true,&quot;showTime&quot;:false,&quot;value&quot;:&quot;2022-03-11T06:00:00.000+03:00&quot;}" data-react-cache-id="common/DateTime-0" class="d-inline-block"><span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2022-03-11 04:00 (GMT+01:00)"><span class="datetime">Mar 11, 2022 </span></span></div>
          - you're done with <span id="student_task_done_percentage">0</span>% of tasks.
      </li>


      <li class="list-group-item">
        <i aria-hidden="true" class="fa fa-check-square  fa-fw"></i>
          Manual QA review was done by Bezaleel Olakunori
            on <div data-react-class="common/DateTime" data-react-props="{&quot;showDate&quot;:true,&quot;showTime&quot;:true,&quot;value&quot;:&quot;2022-03-13T18:33:50.000+03:00&quot;}" data-react-cache-id="common/DateTime-0" class="d-inline-block"><span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2022-03-13 16:33 (GMT+01:00)"><span class="datetime">Mar 13, 2022 4:33 PM</span></span></div>
      </li>


      <div class="gap clean well">
  <h4>In a nutshell…</h4>
  <ul>

      <li>
        <strong>Manual QA review:</strong>
          10.1/13 mandatory
      </li>

    <li>
      <strong>Altogether:</strong>
        &nbsp;<strong>77.69%</strong>
        <ul>
          <li>Mandatory: 77.69%</li>
            <li>Optional: no optional tasks</li>
        </ul>
    </li>
  </ul>
</div>

</ul>




    <div id="project_id" style="display: none" data-project-id="564"></div>




      

      

      <div class="well clean" id="project-description">
  <p><img src="./Project_ Build your portfolio project (Week 2)_ MVP Complete _ ALX Africa Intranet_files/864a45bae8cdb7fa2de1.gif" alt="" style=""></p>

<h2>And now, we ship that MVP!</h2>

<p>This week is <em>still</em> all about execution! Hopefully you are on track and have gotten many of the riskiest aspects of your projects completed. It’s time to integrate all the pieces of your project so that you have a functioning project. The deliverable for the upcoming week will be an MVP and a self-assessment of your project.</p>

<h2>PLD: MVP Review</h2>

<p>During the PLD this week, these are the objectives:</p>

<ul>
<li>Each team meets with 3 teams they didn’t meet with last week, one at a time for 40 minutes.</li>
<li>During the team-team meeting, each team presents for 20 minutes, then observes for 20 minutes. </li>
<li>When a team is presenting, they share their MVP and walk through code any they’ve implemented and technical choices they have made.</li>
<li>When a team is observing, they ask questions, share observations, and code review. Act more as an interviewer than a mentor.</li>
</ul>

<h2>Some things to think about</h2>

<h4>End-to-end</h4>

<p>Prioritize getting all the pieces put together and proving the entire user experience. If you are doing a web project, lets say a food delivery app, it will be important that an order can be placed, received by a delivery-person, and marked as delivered. Refer back to the user stories and ensure each of those workflows is functional.</p>

<h4>If you’re done early</h4>

<p>Keep going! Add more features, tests, and polish the features you’ve completed. If you don’t have ideas for how to enhance your project, then ask your peers.</p>

<h2>More Info</h2>

<h3>Manual QA Review</h3>

<p><strong>It is your responsibility to request a review for your Google Doc from a peer before the project’s deadline. If no peers have been reviewed, you should request a review from a staff member.</strong></p>

</div>


      

      

        
          <h2 class="gap">Tasks</h2>

    <div data-role="task4146" data-position="1" id="task-num-0">
      <div class="panel panel-default task-card " id="task-4146">
  <span id="user_id" data-id="850"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Share your project progress!
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="850"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="4146" data-correction-id="488774">
        <div class="task_progress_bar" style="width: 100%;">
          <div class="task_score_bar" style="width: 100%;">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">100.00%</span> (<span class="task_progress_value">Checks completed: 100.00%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Share a link here to a Google Document where your team provides a written status update. This <strong>can</strong> be the same document you submitted last week, but please make it clear that there is a new entry for this week.</p>

  </div>

  <div class="list-group">
    <!-- Task URLs -->
      <div class="list-group-item">
        <div class="blog_post_div">
          <h4>Add URLs here:</h4>

          <div class="input-group">
            <input id="input_4146" type="text" value="" class="form-control">
            <span class="input-group-btn">
              <button data-task-requesting="0" data-user-id="850" data-task-id="4146" type="button" class="add_task_url btn btn-primary">
                Save
              </button>
            </span>
          </div>

          <div class="task_url_error_msg" data-task-id="4146"></div>

          <ol class="list_4146 sm-gap">
          </ol>

        </div>
      </div>

    <!-- Github information -->

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="4146">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

    <button class="users_done_for_task btn btn-default btn-sm" data-task-id="4146" data-project-id="564" data-toggle="modal" data-target="#task-4146-users-done-modal">
      Help
    </button>
    <div class="modal fade users-done-modal" id="task-4146-users-done-modal" data-task-id="4146" data-project-id="564">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Students who are done with "0. Share your project progress!"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    

      <button class="btn btn-default btn-sm" data-task-id="4146" data-toggle="modal" data-target="#task-qa-review-4146-modal">
        QA Review
      </button>
      <div class="modal fade task_get_qa_review" id="task-qa-review-4146-modal" data-correction-id="488774" data-task-id="4146">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">0. Share your project progress!</h4>
            </div>
            <div class="modal-body">
                <div class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div class="review-container">
                    <div class="review-corrector"></div>
                    <div class="review-github well" style="display:none">
                        <h5>Commit used:</h5>
                        <ul>
                            <li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
                            <li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
                            <li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
                            <li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
                            <li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
                            <li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
                        </ul>
                    </div>
                    <div class="review-percentage_down"></div>
                    <ul class="review-checks list-group sm-gap"></ul>
                    <div class="review-comment"></div>
                </div>
            </div>
        </div>
    </div>
</div>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task4147" data-position="2" id="task-num-1">
      <div class="panel panel-default task-card " id="task-4147">
  <span id="user_id" data-id="850"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      1. GitHub Link
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="850"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="4147" data-correction-id="488774">
        <div class="task_progress_bar" style="width: 100%;">
          <div class="task_score_bar" style="width: 100%;">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">100.00%</span> (<span class="task_progress_value">Checks completed: 100.00%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>Share a link here to your MVP’s Repository</p>

  </div>

  <div class="list-group">
    <!-- Task URLs -->
      <div class="list-group-item">
        <div class="blog_post_div">
          <h4>Add URLs here:</h4>

          <div class="input-group">
            <input id="input_4147" type="text" value="" class="form-control">
            <span class="input-group-btn">
              <button data-task-requesting="0" data-user-id="850" data-task-id="4147" type="button" class="add_task_url btn btn-primary">
                Save
              </button>
            </span>
          </div>

          <div class="task_url_error_msg" data-task-id="4147"></div>

          <ol class="list_4147 sm-gap">
          </ol>

        </div>
      </div>

    <!-- Github information -->

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="4147">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

    <button class="users_done_for_task btn btn-default btn-sm" data-task-id="4147" data-project-id="564" data-toggle="modal" data-target="#task-4147-users-done-modal">
      Help
    </button>
    <div class="modal fade users-done-modal" id="task-4147-users-done-modal" data-task-id="4147" data-project-id="564">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Students who are done with "1. GitHub Link"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    

      <button class="btn btn-default btn-sm" data-task-id="4147" data-toggle="modal" data-target="#task-qa-review-4147-modal">
        QA Review
      </button>
      <div class="modal fade task_get_qa_review" id="task-qa-review-4147-modal" data-correction-id="488774" data-task-id="4147">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">1. GitHub Link</h4>
            </div>
            <div class="modal-body">
                <div class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div class="review-container">
                    <div class="review-corrector"></div>
                    <div class="review-github well" style="display:none">
                        <h5>Commit used:</h5>
                        <ul>
                            <li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
                            <li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
                            <li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
                            <li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
                            <li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
                            <li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
                        </ul>
                    </div>
                    <div class="review-percentage_down"></div>
                    <ul class="review-checks list-group sm-gap"></ul>
                    <div class="review-comment"></div>
                </div>
            </div>
        </div>
    </div>
</div>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task4148" data-position="3" id="task-num-2">
      <div class="panel panel-default task-card " id="task-4148">
  <span id="user_id" data-id="850"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      2. Progress
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="850"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="4148" data-correction-id="488774">
        <div class="task_progress_bar" style="width: 100%;">
          <div class="task_score_bar" style="width: 100%;">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">100.00%</span> (<span class="task_progress_value">Checks completed: 100.00%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>In a section named “Progress” in your status document, answer:</p>

<ul>
<li>On a scale of 1 to 10, how would you rate the progress you’ve made this week?</li>
<li>Provide an explanation of your progress assessment this week.</li>
<li>What parts of your project are completed as planned?</li>
<li>What aspects of your project are incomplete?</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="4148">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

    <button class="users_done_for_task btn btn-default btn-sm" data-task-id="4148" data-project-id="564" data-toggle="modal" data-target="#task-4148-users-done-modal">
      Help
    </button>
    <div class="modal fade users-done-modal" id="task-4148-users-done-modal" data-task-id="4148" data-project-id="564">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Students who are done with "2. Progress"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    

      <button class="btn btn-default btn-sm" data-task-id="4148" data-toggle="modal" data-target="#task-qa-review-4148-modal">
        QA Review
      </button>
      <div class="modal fade task_get_qa_review" id="task-qa-review-4148-modal" data-correction-id="488774" data-task-id="4148">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">2. Progress</h4>
            </div>
            <div class="modal-body">
                <div class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div class="review-container">
                    <div class="review-corrector"></div>
                    <div class="review-github well" style="display:none">
                        <h5>Commit used:</h5>
                        <ul>
                            <li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
                            <li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
                            <li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
                            <li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
                            <li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
                            <li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
                        </ul>
                    </div>
                    <div class="review-percentage_down"></div>
                    <ul class="review-checks list-group sm-gap"></ul>
                    <div class="review-comment"></div>
                </div>
            </div>
        </div>
    </div>
</div>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task4149" data-position="4" id="task-num-3">
      <div class="panel panel-default task-card " id="task-4149">
  <span id="user_id" data-id="850"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      3. Challenges
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="850"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="4149" data-correction-id="488774">
        <div class="task_progress_bar" style="width: 60%;">
          <div class="task_score_bar" style="width: 70%;">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">42.00%</span> (<span class="task_progress_value">Checks completed: 60.00%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>In a section named “Challenges” in your status document, answer:</p>

<ul>
<li>Explain the most difficult technical challenge you encountered in this second week. This answer must be more than 200 words.</li>
<li>Describe the most difficult non-technical challenge you encountered in this second week. This answer must be more than 200 words.</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="4149">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

    <button class="users_done_for_task btn btn-default btn-sm" data-task-id="4149" data-project-id="564" data-toggle="modal" data-target="#task-4149-users-done-modal">
      Help
    </button>
    <div class="modal fade users-done-modal" id="task-4149-users-done-modal" data-task-id="4149" data-project-id="564">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Students who are done with "3. Challenges"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    

      <button class="btn btn-default btn-sm" data-task-id="4149" data-toggle="modal" data-target="#task-qa-review-4149-modal">
        QA Review
      </button>
      <div class="modal fade task_get_qa_review" id="task-qa-review-4149-modal" data-correction-id="488774" data-task-id="4149">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">3. Challenges</h4>
            </div>
            <div class="modal-body">
                <div class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div class="review-container">
                    <div class="review-corrector"></div>
                    <div class="review-github well" style="display:none">
                        <h5>Commit used:</h5>
                        <ul>
                            <li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
                            <li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
                            <li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
                            <li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
                            <li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
                            <li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
                        </ul>
                    </div>
                    <div class="review-percentage_down"></div>
                    <ul class="review-checks list-group sm-gap"></ul>
                    <div class="review-comment"></div>
                </div>
            </div>
        </div>
    </div>
</div>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task4150" data-position="5" id="task-num-4">
      <div class="panel panel-default task-card " id="task-4150">
  <span id="user_id" data-id="850"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      4. Share screenshots
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="850"></span>

    <!-- Progress vs Score -->
      <div class="task_progress_score_bar" data-task-id="4150" data-correction-id="488774">
        <div class="task_progress_bar" style="width: 100%;">
          <div class="task_score_bar" style="width: 100%;">
          </div>
        </div>
        <div class="task_progress_score_text">
          Score: <span class="task_score_value">100.00%</span> (<span class="task_progress_value">Checks completed: 100.00%</span>)
        </div>
      </div>

    <!-- Task Body -->
    <p>In a section named “Screenshots” in your status document, include at least 2 screenshots of your app. </p>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="4150">
      <span class="no"><i aria-hidden="true" class="fa fa-square-o "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa fa-check-square-o "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa fa-spinner  fa-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

    <button class="users_done_for_task btn btn-default btn-sm" data-task-id="4150" data-project-id="564" data-toggle="modal" data-target="#task-4150-users-done-modal">
      Help
    </button>
    <div class="modal fade users-done-modal" id="task-4150-users-done-modal" data-task-id="4150" data-project-id="564">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Students who are done with "4. Share screenshots"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    

      <button class="btn btn-default btn-sm" data-task-id="4150" data-toggle="modal" data-target="#task-qa-review-4150-modal">
        QA Review
      </button>
      <div class="modal fade task_get_qa_review" id="task-qa-review-4150-modal" data-correction-id="488774" data-task-id="4150">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                <h4 class="modal-title">4. Share screenshots</h4>
            </div>
            <div class="modal-body">
                <div class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div class="review-container">
                    <div class="review-corrector"></div>
                    <div class="review-github well" style="display:none">
                        <h5>Commit used:</h5>
                        <ul>
                            <li style="display:none"><strong>User:</strong> <code class="review-github-id"></code> <span class="review-github-name">---</span></li>
                            <li style="display:none"><strong>URL:</strong> <a class="review-github-url" target="_blank">Click here</a></li>
                            <li style="display:none"><strong>ID:</strong> <code class="review-github-commit_id">---</code></li>
                            <li style="display:none"><strong>Author:</strong> <span class="review-github-committer_username">---</span></li>
                            <li style="display:none"><strong>Subject:</strong> <em class="review-github-subject">---</em></li>
                            <li style="display:none"><strong>Date:</strong> <span class="review-github-datetime">---</span></li>
                        </ul>
                    </div>
                    <div class="review-percentage_down"></div>
                    <ul class="review-checks list-group sm-gap"></ul>
                    <div class="review-comment"></div>
                </div>
            </div>
        </div>
    </div>
</div>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>




          <div data-react-class="projects/ProjectReadyForReview" data-react-props="{&quot;canReviewPeerDirectly&quot;:true,&quot;correctCorrectionURI&quot;:&quot;https://alx-intranet.hbtn.io/corrections/488774/correct&quot;,&quot;csrfToken&quot;:&quot;3NWctPwBArUDhuKH4CEKSkFplua68zP6NrbU+r0gedQ5R0c8LA4FaFvj7oidIUwQUOIwz+sdSrwxdGBHMv2+TA==&quot;,&quot;firstReview&quot;:false,&quot;qaReviewsURI&quot;:&quot;/corrections/to_review&quot;,&quot;readyForReviewURI&quot;:&quot;https://alx-intranet.hbtn.io/corrections/488774/toggle_ready_for_review&quot;,&quot;toggled&quot;:true}" data-react-cache-id="projects/ProjectReadyForReview-0"><div class="row gap"><div class="col-md-12"><div class="panel panel-default"><div class="panel-heading"><h3 class="panel-title">Ready for manual review</h3></div><div class="panel-body"><p>Now that you are ready to be reviewed, share your link to your peers...</p><div class="input-group my-2"><span class="form-control user-select-all">https://alx-intranet.hbtn.io/corrections/488774/correct</span><span class="input-group-btn"><a class="btn btn-default"><span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="Click to copy"><span role="button"><i aria-hidden="true" class="fa fa-clipboard fa-fw"></i></span></span></a></span></div><p><strong>... and <a href="https://alx-intranet.hbtn.io/corrections/to_review">review one of them</a>.</strong></p></div></div></div></div></div>



  </div>
</div>


      </article>

      <div class="copyright">Copyright © 2022 ALX, All rights reserved.</div>
    </main>

      <button class="btn btn-primary" id="search-button" data-search-active="false" data-toggle="modal" data-target="#search-modal">
  <i aria-hidden="true" class="fa fa-search "></i>
  <i aria-hidden="true" class="fa fa-window-minimize "></i>
</button>

      <div class="modal fade" id="search-modal" tabindex="-1" role="dialog" aria-labelledby="search-modal-label">
    <div class="modal-dialog modal-md">
        <div class="modal-content">
            <div class="modal-header">
                <div id="search-bar-container">
    <input id="search-bar" type="text" name="hbtn-search-bar" placeholder="✨Start search by typing in this field✨">
</div>

            </div>
            <div class="modal-body">
                <div id="modal-spinner" class="spinner gap">
                    <div class="bounce1"></div>
                    <div class="bounce2"></div>
                    <div class="bounce3"></div>
                </div>
                <div id="search-results-container">
</div>

            </div>
        </div>
    </div>
</div>



      <div class="modal fade" id="markdownGuideModal" tabindex="-1" role="dialog" aria-labelledby="markdownGuideModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-md">
    <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
          <h4 class="modal-title">Markdown Guide</h4>
        </div>
        <div class="modal-body">
            <h4>Emphasis</h4>
<pre>**<strong>bold</strong>**
*<em>italics</em>*
~~<strike>strikethrough</strike>~~</pre>
<h4>Headers</h4>
<pre># Big header
## Medium header
### Small header
#### Tiny header</pre>
<h4>Lists</h4>
<pre>* Generic list item
* Generic list item
* Generic list item

1. Numbered list item
2. Numbered list item
3. Numbered list item</pre>
<h4>Links</h4>
<pre>[Text to display](http://www.example.com)</pre>
<h4>Quotes</h4>
<pre>&gt; This is a quote.
&gt; It can span multiple lines!</pre>
<h4>Images</h4>
<p>CSS style available: <code>width, height, opacity</code></p>
<pre>![](http://www.example.com/image.jpg)
![](http://www.example.com/image.jpg | width: 200px)
![](http://www.example.com/image.jpg | height: 124px | width: 80px | opacity: 0.6)
</pre>
<h4>Tables</h4>
<pre>| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John     | Doe      | Male     |
| Mary     | Smith    | Female   |

<em>Or without aligning the columns...</em>

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John | Doe | Male |
| Mary | Smith | Female |
</pre>
<h4>Displaying code</h4>
<pre>`var example = "hello!";`

<em>Or spanning multiple lines...</em>

```
var example = "hello!";
alert(example);
```</pre>
        </div>
    </div>
  </div>
</div>


      <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
        (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
        m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
        })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

          ga('create',
            'UA-67152800-9',
            'auto', {
              userId: '850'
            }
          );

        ga('send', 'pageview');

        $(document).ready(function() {
          ga(function(tracker) {
            var clientId = tracker.get('clientId');
            $('.ga-client-id').val(clientId);
          });
        });
      </script>




      


  

</body></html>
