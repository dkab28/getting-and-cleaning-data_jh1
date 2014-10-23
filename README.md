



<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>getdata/README.md at master · jamestomasino/getdata</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="jamestomasino/getdata" name="twitter:title" /><meta content="getdata - Coursework for Getting and Cleaning Data Coursera Course" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/201422?v=2&amp;s=400" name="twitter:image:src" />
<meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/201422?v=2&amp;s=400" property="og:image" /><meta content="jamestomasino/getdata" property="og:title" /><meta content="https://github.com/jamestomasino/getdata" property="og:url" /><meta content="getdata - Coursework for Getting and Cleaning Data Coursera Course" property="og:description" />

      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="4066FE21:22E1:660340A:54494BDB" name="octolytics-dimension-request_id" /><meta content="8643900" name="octolytics-actor-id" /><meta content="dkab28" name="octolytics-actor-login" /><meta content="f58d932af6d6001e22d912b79e92040a411934414618c7796597041f6b17193d" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="ZFjxxMZtDCRfJTxRro9ftrsnJRUjx00DL4TAGxfvD51fPtETmIVOd0lgUfMc6Ys6OjchofGrxexupjDwNQaj5Q==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-2d3cae459f0239fa2bbdb6ebb9d4748ed73181e549c982f4468be21db0b36f2f.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://assets-cdn.github.com/assets/github2-8afd77674b7a022523a4b34c73745976faac0598aa9ed5bf6f4713a51f8c44f6.css" media="all" rel="stylesheet" type="text/css" />
    
    


    <meta http-equiv="x-pjax-version" content="2ead3d6374774fa52f629164e8015d5d">

      
  <meta name="description" content="getdata - Coursework for Getting and Cleaning Data Coursera Course">
  <meta name="go-import" content="github.com/jamestomasino/getdata git https://github.com/jamestomasino/getdata.git">

  <meta content="201422" name="octolytics-dimension-user_id" /><meta content="jamestomasino" name="octolytics-dimension-user_login" /><meta content="20627013" name="octolytics-dimension-repository_id" /><meta content="jamestomasino/getdata" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="20627013" name="octolytics-dimension-repository_network_root_id" /><meta content="jamestomasino/getdata" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/jamestomasino/getdata/commits/master.atom" rel="alternate" title="Recent Commits to getdata:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" ga-data-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/jamestomasino/getdata/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/jamestomasino/getdata/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/dkab28" data-ga-click="Header, go to profile, text:username">
      <img alt="dkab28" class="avatar" data-user="8643900" height="20" src="https://avatars3.githubusercontent.com/u/8643900?v=2&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">dkab28</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="jamestomasino/getdata">This repository</span>
    </li>
      <li>
        <a href="/jamestomasino/getdata/issues/new"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="GKzKnTTIyYEASylDL+9y80t5jskf7t9zT4Bj7YR5UVxEkpKSt3MKWq307QBj41nRbwW2f21CGHfXbAc7Gg0UAA==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>


    
  </div>
</div>

      

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="RSX8jwmcMLGkk5n2IA0oOexWfRv7p8DXXQDcdFQJtxTBt8f5nAfd1KX1FIc8UykTR2ZNkAt6XRozwAJ5xJFd1g==" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="20627013" />

    <div class="select-menu js-menu-container js-select-menu">
      <a class="social-count js-social-count" href="/jamestomasino/getdata/watchers">
        1
      </a>
      <a href="/jamestomasino/getdata/subscription"
        class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
        <span class="js-select-button">
          <span class="octicon octicon-eye"></span>
          Watch
        </span>
      </a>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
            <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">Be notified when participating or @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">Be notified of all conversations.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">Never be notified.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/jamestomasino/getdata/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Ft1CIUqyWeuZnsMJSA3vAWNRnW363P0aiC77lDyKeLeI6dpI2i8yb9ljTFcKLkd+PP/0Jwb3S3TdbHcdFj5R5Q==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Unstar this repository" title="Unstar jamestomasino/getdata">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/jamestomasino/getdata/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/jamestomasino/getdata/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="1I9ufuxAGr2Yo+T8yjBPf9ATxRgJY3/0LVQ1lfTeCEf1JQ3DmH3yL9CKpF4SaU2dM6rMWt6WXNl9drCFt194wQ==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Star this repository" title="Star jamestomasino/getdata">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/jamestomasino/getdata/stargazers">
          0
        </a>
</form>  </div>

  </li>


        <li>
          <a href="/jamestomasino/getdata/fork" class="minibutton with-count js-toggler-target fork-button tooltipped-n" title="Fork your own copy of jamestomasino/getdata to your account" aria-label="Fork your own copy of jamestomasino/getdata to your account" rel="nofollow" data-method="post">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/jamestomasino/getdata/network" class="social-count">0</a>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/jamestomasino" class="url fn" itemprop="url" rel="author"><span itemprop="title">jamestomasino</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/jamestomasino/getdata" class="js-current-repository js-repo-home-link" data-pjax-container-selector="#js-repo-pjax-container">getdata</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<div class="sunken-menu vertical-right repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders" role="navigation" data-issue-count-url="/jamestomasino/getdata/issues/counts" data-pjax-container-selector="#js-repo-pjax-container">
  <div class="sunken-menu-contents">
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Code">
        <a href="/jamestomasino/getdata" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-pjax="true" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /jamestomasino/getdata">
          <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

        <li class="tooltipped tooltipped-w" aria-label="Issues">
          <a href="/jamestomasino/getdata/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /jamestomasino/getdata/issues">
            <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
            <span class="js-issue-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>

      <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
        <a href="/jamestomasino/getdata/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g p" data-selected-links="repo_pulls /jamestomasino/getdata/pulls">
            <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
            <span class="js-pull-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>


        <li class="tooltipped tooltipped-w" aria-label="Wiki">
          <a href="/jamestomasino/getdata/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g w" data-selected-links="repo_wiki /jamestomasino/getdata/wiki">
            <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>
    </ul>
    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">

      <li class="tooltipped tooltipped-w" aria-label="Pulse">
        <a href="/jamestomasino/getdata/pulse/weekly" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="pulse /jamestomasino/getdata/pulse/weekly">
          <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped tooltipped-w" aria-label="Graphs">
        <a href="/jamestomasino/getdata/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="repo_graphs repo_contributors /jamestomasino/getdata/graphs">
          <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>


  </div>
</div>

              <div class="only-with-full-nav">
                
  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/jamestomasino/getdata.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/jamestomasino/getdata.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="git@github.com:jamestomasino/getdata.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="git@github.com:jamestomasino/getdata.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/jamestomasino/getdata" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/jamestomasino/getdata" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>


<p class="clone-options">You can clone with
      <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>,
      <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>,
      or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="github-windows://openRepo/https://github.com/jamestomasino/getdata" class="minibutton sidebar-button" title="Save jamestomasino/getdata to your computer and use it in GitHub Desktop." aria-label="Save jamestomasino/getdata to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/jamestomasino/getdata/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download the contents of jamestomasino/getdata as a zip file"
                   title="Download the contents of jamestomasino/getdata as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/jamestomasino/getdata/blob/cc60136bfae549752e04a78bcd22f70c8344329a/courseproject/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:88538a6cd1d4dab1816976b8f67d7cee -->

<div class="file-navigation">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div> <!-- /.select-menu-header -->

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div><!-- /.select-menu-tabs -->
      </div><!-- /.select-menu-filters -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/jamestomasino/getdata/blob/master/courseproject/README.md"
                 data-name="master"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="button-group right">
    <a href="/jamestomasino/getdata/find/master"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button class="js-zeroclipboard minibutton zeroclipboard-button"
          data-clipboard-text="courseproject/README.md"
          aria-label="Copy to clipboard"
          data-copied-hint="Copied!">
      <span class="octicon octicon-clippy"></span>
    </button>
  </div>

  <div class="breadcrumb">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/jamestomasino/getdata" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">getdata</span></a></span></span><span class="separator"> / </span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/jamestomasino/getdata/tree/master/courseproject" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">courseproject</span></a></span><span class="separator"> / </span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="James Tomasino" class="avatar" data-user="201422" height="24" src="https://avatars0.githubusercontent.com/u/201422?v=2&amp;s=48" width="24" />
        <span class="author"><a href="/jamestomasino" rel="author">jamestomasino</a></span>
        <time datetime="2014-06-22T20:09:26Z" is="relative-time">Jun 22, 2014</time>
        <div class="commit-title">
            <a href="/jamestomasino/getdata/commit/78642628d9a336e1a821fc5d52821d9875e9b05a" class="message" data-pjax="true" title="added full readme">added full readme</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="James Tomasino" data-user="201422" height="24" src="https://avatars0.githubusercontent.com/u/201422?v=2&amp;s=48" width="24" />
            <a href="/jamestomasino">jamestomasino</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file-box">
  <div class="file">
    <div class="meta clearfix">
      <div class="info file-name">
          <span>123 lines (83 sloc)</span>
          <span class="meta-divider"></span>
        <span>4.597 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
          <a href="/jamestomasino/getdata/raw/master/courseproject/README.md" class="minibutton " id="raw-url">Raw</a>
            <a href="/jamestomasino/getdata/blame/master/courseproject/README.md" class="minibutton js-update-url-with-hash">Blame</a>
          <a href="/jamestomasino/getdata/commits/master/courseproject/README.md" class="minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->

          <a class="octicon-button tooltipped tooltipped-nw"
             href="github-windows://openRepo/https://github.com/jamestomasino/getdata?branch=master&amp;filepath=courseproject%2FREADME.md" aria-label="Open this file in GitHub for Windows">
              <span class="octicon octicon-device-desktop"></span>
          </a>

              <a class="octicon-button tooltipped tooltipped-n js-update-url-with-hash"
                 aria-label="Clicking this button will fork this project so you can edit the file"
                 href="/jamestomasino/getdata/edit/master/courseproject/README.md"
                 data-method="post" rel="nofollow"><span class="octicon octicon-pencil"></span></a>

            <a class="octicon-button danger tooltipped tooltipped-s"
               href="/jamestomasino/getdata/delete/master/courseproject/README.md"
               aria-label="Fork this project and delete file"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">
          <span class="octicon octicon-trashcan"></span>
        </a>
      </div><!-- /.actions -->
    </div>
      <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h2>
<a name="user-content-course-project" class="anchor" href="#course-project" aria-hidden="true"><span class="octicon octicon-link"></span></a>Course Project</h2>

<h3>
<a name="user-content-overview" class="anchor" href="#overview" aria-hidden="true"><span class="octicon octicon-link"></span></a>Overview</h3>

<p>The purpose of this project is to demonstrate your ability to collect, work
with, and clean a data set. The goal is to prepare tidy data that can be used
for later analysis. You will be graded by your peers on a series of yes/no
questions related to the project. You will be required to submit: 1) a tidy
data set as described below, 2) a link to a Github repository with your script
for performing the analysis, and 3) a code book that describes the variables,
the data, and any transformations or work that you performed to clean up the
data called <code>CodeBook.md</code>. You should also include a <code>README.md</code> in the repo
with your scripts. This repo explains how all of the scripts work and how they
are connected.</p>

<p>One of the most exciting areas in all of data science right now is wearable
computing - see for example this article . Companies like Fitbit, Nike, and
Jawbone Up are racing to develop the most advanced algorithms to attract new
users. The data linked to from the course website represent data collected from
the accelerometers from the Samsung Galaxy S smartphone. A full description is
available at the site where the data was obtained:</p>

<pre><code>http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
</code></pre>

<p>Here are the data for the project:</p>

<pre><code>https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
</code></pre>

<p>You should create one R script called <code>run_analysis.R</code> that does the following. </p>

<ol class="task-list">
<li>Merges the training and the test sets to create one data set.</li>
<li>Extracts only the measurements on the mean and standard deviation for each
measurement.</li>
<li>Uses descriptive activity names to name the activities in the data set</li>
<li>Appropriately labels the data set with descriptive variable names. </li>
<li>Creates a second, independent tidy data set with the average of each
variable for each activity and each subject. </li>
</ol>

<p>Good luck!</p>

<h3>
<a name="user-content-evaluation-checklist" class="anchor" href="#evaluation-checklist" aria-hidden="true"><span class="octicon octicon-link"></span></a>Evaluation Checklist</h3>

<h4>
<a name="user-content-tidy-data-set" class="anchor" href="#tidy-data-set" aria-hidden="true"><span class="octicon octicon-link"></span></a>Tidy Data Set</h4>

<p><em>From Question:</em> Please upload a tidy data set according to the instructions
in the project description. Please upload your data set as a separate file (do
not cut and paste a dataset directly into the text box, as this may cause
errors saving your submission). </p>

<p><em>From Evaluation:</em> Has the student submitted a tidy data set? </p>

<h4>
<a name="user-content-second-data-set" class="anchor" href="#second-data-set" aria-hidden="true"><span class="octicon octicon-link"></span></a>Second Data Set</h4>

<p><em>From Question:</em> Creates a second, independent tidy data set with the average
of each variable for each activity and each subject.</p>

<h4>
<a name="user-content-github-repo-with-required-scripts" class="anchor" href="#github-repo-with-required-scripts" aria-hidden="true"><span class="octicon octicon-link"></span></a>Github Repo with Required Scripts</h4>

<p><em>From Question:</em> Please submit a link to a Github repo with the code for
performing your analysis. The code should have a file <code>run_analysis.R</code> in the
main directory that can be run as long as the Samsung data is in your working
directory.  The output should be the tidy data set you submitted for part 1.</p>

<p><em>From Evaluation:</em> Did the student submit a Github repo with the required
scripts?</p>

<h4>
<a name="user-content-code-book" class="anchor" href="#code-book" aria-hidden="true"><span class="octicon octicon-link"></span></a>Code Book</h4>

<p><em>From Overview:</em> A code book that describes the variables, the data, and any
transformations or work that you performed to clean up the data called
<code>CodeBook.md</code>.</p>

<p><em>From Evaluation:</em> Please submit a code book that modifies and updates the
codebooks available to you with the data to indicate all the variables and
summaries you calculated, along with units, and any other relevant information.</p>

<h4>
<a name="user-content-readme" class="anchor" href="#readme" aria-hidden="true"><span class="octicon octicon-link"></span></a>README</h4>

<p><em>From Overview:</em> You should also include a <code>README.md</code> in the repo with your
scripts. This repo explains how all of the scripts work and how they are
connected.</p>

<p><em>From Question:</em> You should include a <code>README.md</code> in the repo describing how
the script works.</p>

<p><em>From Evaluation:</em> I was able to follow the README in the directory that
explained what the analysis files did. </p>

<h3>
<a name="user-content-data-analysis-explanation" class="anchor" href="#data-analysis-explanation" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Analysis Explanation</h3>

<h4>
<a name="user-content-for-1st-tiny-data-set" class="anchor" href="#for-1st-tiny-data-set" aria-hidden="true"><span class="octicon octicon-link"></span></a>For 1st tiny data set:</h4>

<ul class="task-list">
<li>Read data sets and combine them</li>
<li>Read subjects and combine them</li>
<li>Read data labels and combine them</li>
<li>Read features list</li>
<li>Subset only only std and mean features from list</li>
<li>Perform same subset on data set</li>
<li>Rename features to be more human readable</li>
<li>Read activity list</li>
<li>Rename activities to be more human readable</li>
<li>Rename data labels with activity name</li>
<li>Merge data, subjects, and labels to single tiny data set</li>
<li>Write tiny data set to file</li>
</ul>

<h4>
<a name="user-content-for-2nd-tiny-data-set-average-of-measurement-for-activity-and-subject" class="anchor" href="#for-2nd-tiny-data-set-average-of-measurement-for-activity-and-subject" aria-hidden="true"><span class="octicon octicon-link"></span></a>For 2nd tiny data set: average of measurement for activity and subject</h4>

<ul class="task-list">
<li>Prepare empty data set of appropriate length for </li>
<li>Loop through subjects, then subloop through activities</li>
<li>For each activity in a subject, get the full list of measurements</li>
<li>Calculate the mean of each of these activities</li>
<li>Place the means in subsequent columns of the subject/activity row</li>
<li>Write second tiny data set to file</li>
</ul>
</article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="https://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2014 <span title="0.04556s from github-fe136-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents js-suggester-field" placeholder=""></textarea>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-dabc650f8a51dffd1d4376a3522cbda5536e4807e01d2a86ff7e60d8d6ee3029.js" type="text/javascript"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-d01013daa80c5a341ba3ddb684f2f26679eb369d67459151d5175a634a9e98a5.js" type="text/javascript"></script>
      
      
  </body>
</html>

