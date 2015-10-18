


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>RepData_PeerAssessment1/PA1_template.Rmd at master · hyperbeam2/RepData_PeerAssessment1</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="hyperbeam2/RepData_PeerAssessment1" name="twitter:title" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" name="twitter:description" /><meta content="https://avatars0.githubusercontent.com/u/12692701?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars0.githubusercontent.com/u/12692701?v=3&amp;s=400" property="og:image" /><meta content="hyperbeam2/RepData_PeerAssessment1" property="og:title" /><meta content="https://github.com/hyperbeam2/RepData_PeerAssessment1" property="og:url" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTI2OTI3MDE6NWQ3MWE5NzA2YTk0N2YzY2VhYTQ5MTJjZTZkZjg1NTk6MDQ4YTJhNjUzZjE3YmZkMWJmMWJhNmFjNTJiMGIyYjY0OTJiZTkxOTljMzBjNTVlMGI5MDgwNGIwYzYwMDU5Mg==--beb210eb083ec282f6e13025b5ab1f13fdb8b53a">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="D2BA3B2A:7D24:9F17167:5623A5BD" name="octolytics-dimension-request_id" /><meta content="12692701" name="octolytics-actor-id" /><meta content="hyperbeam2" name="octolytics-actor-login" /><meta content="171cc96a01d038aca470f641fa3412e61f1e6389f570bb0b1e7b9215756a007c" name="octolytics-actor-hash" />

<meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />


  <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta class="js-ga-set" name="dimension4" content="Current repo nav">




    <meta name="is-dotcom" content="true">
        <meta name="hostname" content="github.com">
    <meta name="user-login" content="hyperbeam2">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="1d1a5b5836f9a46395aba3701977b7e72620087d" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-1c72e5e1cbdeae0d6a25ee0e6f07ae0100db5696d3f5f10ed2acf1f0885ef5f0.css" integrity="sha256-HHLl4cverg1qJe4ObweuAQDbVpbT9fEO0qzx8Ihe9fA=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-91f10774cc492e563a1bcd77a9b935a21bffbda4c7fefb5ed448d51a53217852.css" integrity="sha256-kfEHdMxJLlY6G813qbk1ohv/vaTH/vte1EjVGlMheFI=" media="all" rel="stylesheet" />
    
    
    


    <meta http-equiv="x-pjax-version" content="aaf0a95e6a9bf84b40427e5620ea23c2">

      
  <meta name="description" content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research">
  <meta name="go-import" content="github.com/hyperbeam2/RepData_PeerAssessment1 git https://github.com/hyperbeam2/RepData_PeerAssessment1.git">

  <meta content="12692701" name="octolytics-dimension-user_id" /><meta content="hyperbeam2" name="octolytics-dimension-user_login" /><meta content="44477415" name="octolytics-dimension-repository_id" /><meta content="hyperbeam2/RepData_PeerAssessment1" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="16709733" name="octolytics-dimension-repository_parent_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_parent_nwo" /><meta content="16709733" name="octolytics-dimension-repository_network_root_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/hyperbeam2/RepData_PeerAssessment1/commits/master.atom" rel="alternate" title="Recent Commits to RepData_PeerAssessment1:master" type="application/atom+xml">

  </head>


  <body class="logged_in   env-production windows vis-public fork page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/hyperbeam2/RepData_PeerAssessment1/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/hyperbeam2/RepData_PeerAssessment1/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:hyperbeam2"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-bell"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="hyperbeam2/RepData_PeerAssessment1">This repository</span>
  </div>
    <a class="dropdown-item" href="/hyperbeam2/RepData_PeerAssessment1/settings/collaboration" data-ga-click="Header, create new collaborator">
      New collaborator
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="/hyperbeam2"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@hyperbeam2" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/12692701?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">hyperbeam2</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/hyperbeam2" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ybYmJE+MzlPN67OWC6JjRBOuJu2LFIedMQ6H9lWzvglsbYX8PDGR8lg6Js7K6dkWZtVnLKl09SZyvxO3srCGtQ==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

      

      


    <div id="start-of-content" class="accessibility-aid"></div>

    <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/WebPage">
    <div class="pagehead repohead instapaper_ignore readability-menu">

      <div class="container">

        <div class="clearfix">
          

<ul class="pagehead-actions">

  <li>
      <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="NufeeVSidjjvfsWMMLukLy740YLFu8UNhybDZvHvKC/Rt2HlKNpXWx7+YNSi13IJmJeugM7Hs/DuJNClT1Xx2A==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="44477415" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/hyperbeam2/RepData_PeerAssessment1/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Unwatch
          </span>
        </a>
        <a class="social-count js-social-count" href="/hyperbeam2/RepData_PeerAssessment1/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/hyperbeam2/RepData_PeerAssessment1/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="KBs9A7dEk/ugepWlVAb2I3y+VYGyaMVMQN+G5lVdzsPNCver4qmze1dUO5zt0cah1N894hiGSjN1vQpl+xTrGw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar hyperbeam2/RepData_PeerAssessment1"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/hyperbeam2/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/hyperbeam2/RepData_PeerAssessment1/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="I9kh2I7wwTw0giJztAogAb/RGfQIT+TAEcypMeLaQ9g4ZMFkEraLC1FoHWgPad31++lBaVjlcx3WJ1kCblgJbA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star hyperbeam2/RepData_PeerAssessment1"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/hyperbeam2/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/hyperbeam2/RepData_PeerAssessment1/fork" class="btn-with-count" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="hbMkgBM0WVxni2Z+O7jTpP+XAHcGnQwIczYG1gYldDaLX7Rq6ru8aKQM+ue6t2c2F+H7C6fmvjSSuYg5b30jVg==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of hyperbeam2/RepData_PeerAssessment1 to your account"
                aria-label="Fork your own copy of hyperbeam2/RepData_PeerAssessment1 to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
</form>
    <a href="/hyperbeam2/RepData_PeerAssessment1/network" class="social-count">
      19,283
    </a>
  </li>
</ul>

          <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span class="mega-octicon octicon-repo-forked"></span>
  <span class="author"><a href="/hyperbeam2" class="url fn" itemprop="url" rel="author"><span itemprop="title">hyperbeam2</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/hyperbeam2/RepData_PeerAssessment1" data-pjax="#js-repo-pjax-container">RepData_PeerAssessment1</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

    <span class="fork-flag">
      <span class="text">forked from <a href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
    </span>
</h1>

        </div>
      </div>
    </div>

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline ">
        <div class="repository-sidebar clearfix">
          
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/hyperbeam2/RepData_PeerAssessment1/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/hyperbeam2/RepData_PeerAssessment1" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /hyperbeam2/RepData_PeerAssessment1">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>


    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/hyperbeam2/RepData_PeerAssessment1/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /hyperbeam2/RepData_PeerAssessment1/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/hyperbeam2/RepData_PeerAssessment1/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /hyperbeam2/RepData_PeerAssessment1/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/hyperbeam2/RepData_PeerAssessment1/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /hyperbeam2/RepData_PeerAssessment1/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/hyperbeam2/RepData_PeerAssessment1/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /hyperbeam2/RepData_PeerAssessment1/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Settings">
        <a href="/hyperbeam2/RepData_PeerAssessment1/settings" aria-label="Settings" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_settings repo_branch_settings hooks /hyperbeam2/RepData_PeerAssessment1/settings">
          <span class="octicon octicon-gear"></span> <span class="full-word">Settings</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>
</nav>

            <div class="only-with-full-nav">
                
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3 class="text-small"><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/hyperbeam2/RepData_PeerAssessment1.git" readonly="readonly" aria-label="HTTPS clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3 class="text-small"><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:hyperbeam2/RepData_PeerAssessment1.git" readonly="readonly" aria-label="SSH clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3 class="text-small"><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/hyperbeam2/RepData_PeerAssessment1" readonly="readonly" aria-label="Subversion checkout URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options text-small">You can clone with
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=push" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="46pzQmzoW55uJvpTwYUrTJztl0AJnehX/bXnWzb6ZQSP/GZSVqNvFDIZ82t4qMu7H0zVehH0l/ltK+9np1pe1Q==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=push" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="86BNkaZlteglSE1mWojhWabcpbqtH/yCohRwA5PW9P3ctnXO2ela6GubPSv1el+NaKgv0RhMs5MGe4amMLsEXQ==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=push" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="kD7zFTM4wop0E+pzddaZXZjMiV2+siqDYF7qBt4viirmCblDyXqmU9gDItLqVXk1M2oO8Xd9Abfa4flhTvoOWQ==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>
  <a href="github-windows://openRepo/https://github.com/hyperbeam2/RepData_PeerAssessment1" class="btn btn-sm sidebar-button" title="Save hyperbeam2/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop." aria-label="Save hyperbeam2/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-desktop-download"></span>
    Clone in Desktop
  </a>

              <a href="/hyperbeam2/RepData_PeerAssessment1/archive/master.zip"
                 class="btn btn-sm sidebar-button"
                 aria-label="Download the contents of hyperbeam2/RepData_PeerAssessment1 as a zip file"
                 title="Download the contents of hyperbeam2/RepData_PeerAssessment1 as a zip file"
                 rel="nofollow">
                <span class="octicon octicon-cloud-download"></span>
                Download ZIP
              </a>
            </div>
        </div>
        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/hyperbeam2/RepData_PeerAssessment1/blob/c28099134263f59b7a646a514477681a4a3aba7f/PA1_template.Rmd" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:d82f3c2b4dfd9031cd5c06c4313f3da8 -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/hyperbeam2/RepData_PeerAssessment1/blob/master/PA1_template.Rmd"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/hyperbeam2/RepData_PeerAssessment1/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="zj0Z3PJuWRHpajlMfzAqeiLyqDErF97HSX4mYKJFh+cQGR0ytVbTp3jZo4xxt91W2FEW2Q1eMvdPPxHRW++O2g==" /></div>
            <span class="octicon octicon-git-branch select-menu-item-icon"></span>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘master’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
            <input type="hidden" name="path" id="path" value="PA1_template.Rmd">
</form>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="btn-group right">
      <a href="/hyperbeam2/RepData_PeerAssessment1/find/master"
            class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-nw"
            data-pjax
            data-hotkey="t"
            aria-label="Quickly jump between files">
        <span class="octicon octicon-list-unordered"></span>
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </div>

    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/hyperbeam2/RepData_PeerAssessment1" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">RepData_PeerAssessment1</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.Rmd</strong>
    </div>
  </div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/hyperbeam2/RepData_PeerAssessment1/commit/c28099134263f59b7a646a514477681a4a3aba7f" data-pjax>
          c28099
        </a>
        <time datetime="2015-10-18T13:59:20Z" is="relative-time">Oct 18, 2015</time>
      </span>
      <div>
        <img alt="@hyperbeam2" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/12692701?v=3&amp;s=40" width="20" />
        <a href="/hyperbeam2" class="user-mention" rel="author">hyperbeam2</a>
          <a href="/hyperbeam2/RepData_PeerAssessment1/commit/c28099134263f59b7a646a514477681a4a3aba7f" class="message" data-pjax="true" title="Update PA1_template.Rmd">Update PA1_template.Rmd</a>
      </div>

    <div class="commit-tease-contributors">
      <a class="muted-link contributors-toggle" href="#blob_contributors_box" rel="facebox">
        <strong>3</strong>
         contributors
      </a>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="hyperbeam2" href="/hyperbeam2/RepData_PeerAssessment1/commits/master/PA1_template.Rmd?author=hyperbeam2"><img alt="@hyperbeam2" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/12692701?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="rdpeng" href="/hyperbeam2/RepData_PeerAssessment1/commits/master/PA1_template.Rmd?author=rdpeng"><img alt="@rdpeng" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/9612?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="Ripley6811" href="/hyperbeam2/RepData_PeerAssessment1/commits/master/PA1_template.Rmd?author=Ripley6811"><img alt="@Ripley6811" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/1886005?v=3&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@hyperbeam2" height="24" src="https://avatars0.githubusercontent.com/u/12692701?v=3&amp;s=48" width="24" />
            <a href="/hyperbeam2">hyperbeam2</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@rdpeng" height="24" src="https://avatars0.githubusercontent.com/u/9612?v=3&amp;s=48" width="24" />
            <a href="/rdpeng">rdpeng</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@Ripley6811" height="24" src="https://avatars0.githubusercontent.com/u/1886005?v=3&amp;s=48" width="24" />
            <a href="/Ripley6811">Ripley6811</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/hyperbeam2/RepData_PeerAssessment1/raw/master/PA1_template.Rmd" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/hyperbeam2/RepData_PeerAssessment1/blame/master/PA1_template.Rmd" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/hyperbeam2/RepData_PeerAssessment1/commits/master/PA1_template.Rmd" class="btn btn-sm " rel="nofollow">History</a>
    </div>

      <a class="octicon-btn tooltipped tooltipped-nw"
         href="github-windows://openRepo/https://github.com/hyperbeam2/RepData_PeerAssessment1?branch=master&amp;filepath=PA1_template.Rmd"
         aria-label="Open this file in GitHub Desktop"
         data-ga-click="Repository, open with desktop, type:windows">
          <span class="octicon octicon-device-desktop"></span>
      </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/hyperbeam2/RepData_PeerAssessment1/edit/master/PA1_template.Rmd" class="inline-form js-update-url-with-hash" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="9hYzDjUsnpuVpW2b/dFaJoODcaIeCbD7jO/gmba8yeHfquDJcLspPLe1f4uy1v8bl0H7Aaf92XJCFECFk9kNrg==" /></div>
          <button class="octicon-btn tooltipped tooltipped-nw" type="submit"
            aria-label="Edit this file" data-hotkey="e" data-disable-with>
            <span class="octicon octicon-pencil"></span>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/hyperbeam2/RepData_PeerAssessment1/delete/master/PA1_template.Rmd" class="inline-form" data-form-nonce="1d1a5b5836f9a46395aba3701977b7e72620087d" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="lHVgkcADSLkNKrZ3lEhhK+nnNzSK4Wv4fUOrO993p3kMqFGo8q8bj5BPHQ5N/z78V334zWQtOzvTqnZvdt3rwA==" /></div>
          <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete this file" data-disable-with>
            <span class="octicon octicon-trashcan"></span>
          </button>
</form>  </div>

  <div class="file-info">
      96 lines (83 sloc)
      <span class="file-info-divider"></span>
    4.34 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h2><a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and preprocessing the data</h2>

<div class="highlight highlight-source-r"><pre><span class="pl-v">echo</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>
unzip(<span class="pl-s"><span class="pl-pds">"</span>activity.zip<span class="pl-pds">"</span></span>)
<span class="pl-smi">data</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>,<span class="pl-v">colClasses</span> <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">"</span>integer<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>Date<span class="pl-pds">"</span></span>,<span class="pl-s"><span class="pl-pds">"</span>factor<span class="pl-pds">"</span></span>))
<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">month</span> <span class="pl-k">&lt;-</span> as.numeric(format(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>,<span class="pl-s"><span class="pl-pds">"</span>%m<span class="pl-pds">"</span></span>))
<span class="pl-smi">expelNA</span> <span class="pl-k">&lt;-</span> na.omit(<span class="pl-smi">data</span>)</pre></div>

<h2><a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is mean total number of steps taken per day?</h2>

<div class="highlight highlight-source-r"><pre>ggplot(<span class="pl-smi">expelNA</span>, aes(<span class="pl-smi">date</span>, <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_bar(<span class="pl-v">stat</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>identity<span class="pl-pds">"</span></span>, <span class="pl-v">colour</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>, <span class="pl-v">fill</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>, <span class="pl-v">width</span> <span class="pl-k">=</span> <span class="pl-c1">0.7</span>) <span class="pl-k">+</span> facet_grid(. <span class="pl-k">~</span> <span class="pl-smi">month</span>, <span class="pl-v">scales</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>free<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> labs(<span class="pl-v">title</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Histogram of Total Number of Steps Taken Each Day<span class="pl-pds">"</span></span>, <span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Date<span class="pl-pds">"</span></span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Total number of steps<span class="pl-pds">"</span></span>)
<span class="pl-smi">totalSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">expelNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-k">list</span>(<span class="pl-v">Date</span> <span class="pl-k">=</span> <span class="pl-smi">expelNA</span><span class="pl-k">$</span><span class="pl-smi">date</span>), <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>sum<span class="pl-pds">"</span></span>)<span class="pl-k">$</span><span class="pl-smi">x</span>
mean(<span class="pl-smi">totalSteps</span>)
median(<span class="pl-smi">totalSteps</span>)</pre></div>

<h2><a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the average daily activity pattern?</h2>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">avgSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">expelNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-k">list</span>(<span class="pl-v">interval</span> <span class="pl-k">=</span> as.numeric(as.character(<span class="pl-smi">expelNA</span><span class="pl-k">$</span><span class="pl-smi">interval</span>))), <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>mean<span class="pl-pds">"</span></span>)
names(<span class="pl-smi">avgSteps</span>)[<span class="pl-c1">2</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>meanOfSteps<span class="pl-pds">"</span></span>
ggplot(<span class="pl-smi">avgSteps</span>, aes(<span class="pl-smi">interval</span>, <span class="pl-smi">meanOfSteps</span>)) <span class="pl-k">+</span> geom_line(<span class="pl-v">color</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>, <span class="pl-v">size</span> <span class="pl-k">=</span> <span class="pl-c1">0.8</span>) <span class="pl-k">+</span> labs(<span class="pl-v">title</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Time Series Plot of the 5-minute Interval<span class="pl-pds">"</span></span>, <span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>5-minute intervals<span class="pl-pds">"</span></span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Average Number of Steps Taken<span class="pl-pds">"</span></span>)</pre></div>

<p>On average across all the days in the dataset, the 5-minute interval contains the maximum number of steps?</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">avgSteps</span>[<span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span> <span class="pl-k">==</span> max(<span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span>), ]</pre></div>

<h2><a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing missing values</h2>

<p>Calculate and report the total number of missing values in the dataset (i.e. the total number of rows with NAs)</p>

<div class="highlight highlight-source-r"><pre>sum(is.na(<span class="pl-smi">data</span>))</pre></div>

<p>Devise a strategy for filling in all of the missing values in the dataset. The strategy does not need to be sophisticated. For example, you could use the mean/median for that day, or the mean for that 5-minute interval, etc.</p>

<ul>
<li>Fill up using mean for that 5-minute interval</li>
</ul>

<p>Create a new dataset that is equal to the original dataset but with the missing data filled in.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">newData</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">data</span> 
<span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span>nrow(<span class="pl-smi">newData</span>)) {
  <span class="pl-k">if</span> (is.na(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">i</span>])) {
    <span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">i</span>] <span class="pl-k">&lt;-</span> <span class="pl-smi">avgSteps</span>[which(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">interval</span>[<span class="pl-smi">i</span>] <span class="pl-k">==</span> <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">interval</span>), ]<span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span>
  }
}</pre></div>

<p>Make a histogram of the total number of steps taken each day and Calculate and report the mean and median total number of steps taken per day. Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data on the estimates of the total daily number of steps?</p>

<div class="highlight highlight-source-r"><pre>ggplot(<span class="pl-smi">newData</span>, aes(<span class="pl-smi">date</span>, <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_bar(<span class="pl-v">stat</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>identity<span class="pl-pds">"</span></span>,
                                             <span class="pl-v">colour</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>,
                                             <span class="pl-v">fill</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>,
                                             <span class="pl-v">width</span> <span class="pl-k">=</span> <span class="pl-c1">0.7</span>) <span class="pl-k">+</span> facet_grid(. <span class="pl-k">~</span> <span class="pl-smi">month</span>, <span class="pl-v">scales</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>free<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> labs(<span class="pl-v">title</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Histogram of Total Number of Steps Taken Each Day (no missing data)<span class="pl-pds">"</span></span>, <span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Date<span class="pl-pds">"</span></span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Total number of steps<span class="pl-pds">"</span></span>)

<span class="pl-smi">newTotalSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, 
                           <span class="pl-k">list</span>(<span class="pl-v">Date</span> <span class="pl-k">=</span> <span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">date</span>), 
                           <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>sum<span class="pl-pds">"</span></span>)<span class="pl-k">$</span><span class="pl-smi">x</span>
<span class="pl-smi">newMean</span> <span class="pl-k">&lt;-</span> mean(<span class="pl-smi">newTotalSteps</span>)
<span class="pl-smi">newMedian</span> <span class="pl-k">&lt;-</span> median(<span class="pl-smi">newTotalSteps</span>)
<span class="pl-smi">oldMean</span> <span class="pl-k">&lt;-</span> mean(<span class="pl-smi">totalSteps</span>)
<span class="pl-smi">oldMedian</span> <span class="pl-k">&lt;-</span> median(<span class="pl-smi">totalSteps</span>)
<span class="pl-smi">newMean</span> <span class="pl-k">-</span> <span class="pl-smi">oldMean</span>
<span class="pl-smi">newMedian</span> <span class="pl-k">-</span> <span class="pl-smi">oldMedian</span></pre></div>

<p>New mean and old mean are the same, but new median is greater than old median</p>

<h2><a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<ul>
<li>Create a new factor variable in the dataset with two levels -- "weekday" and "weekend" indicating whether a given date is a weekday or weekend day. </li>
</ul>

<div class="highlight highlight-source-r"><pre>head(<span class="pl-smi">newData</span>)
<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span> <span class="pl-k">&lt;-</span> <span class="pl-k">factor</span>(format(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-s"><span class="pl-pds">"</span>%A<span class="pl-pds">"</span></span>))
levels(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>)
levels(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>) <span class="pl-k">&lt;-</span> <span class="pl-k">list</span>(<span class="pl-v">weekday</span> <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">"</span>Monday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Tuesday<span class="pl-pds">"</span></span>,
                                             <span class="pl-s"><span class="pl-pds">"</span>Wednesday<span class="pl-pds">"</span></span>, 
                                             <span class="pl-s"><span class="pl-pds">"</span>Thursday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Friday<span class="pl-pds">"</span></span>),
                                 <span class="pl-v">weekend</span> <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>))
levels(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>)
table(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>)</pre></div>

<ul>
<li>Make a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis).</li>
</ul>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">avgSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, 
                      <span class="pl-k">list</span>(<span class="pl-v">interval</span> <span class="pl-k">=</span> as.numeric(as.character(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">interval</span>)), 
                           <span class="pl-v">weekdays</span> <span class="pl-k">=</span> <span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>),
                      <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>mean<span class="pl-pds">"</span></span>)
names(<span class="pl-smi">avgSteps</span>)[<span class="pl-c1">3</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>meanOfSteps<span class="pl-pds">"</span></span>
library(<span class="pl-smi">lattice</span>)
xyplot(<span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span> <span class="pl-k">~</span> <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">|</span> <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>, 
       <span class="pl-v">layout</span> <span class="pl-k">=</span> c(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>), <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, 
       <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Interval<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Number of steps<span class="pl-pds">"</span></span>)</pre></div>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>
      </div>
      <div class="modal-backdrop"></div>
    </div>
  </div>


    </div>

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing">Pricing</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.06339s from github-fe137-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" integrity="sha256-CA8cFVoo9aQxXUpoYq6vt+J7ygp022966eAEjjITadE=" src="https://assets-cdn.github.com/assets/frameworks-080f1c155a28f5a4315d4a6862aeafb7e27bca0a74db6f7ae9e0048e321369d1.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-rAM/AGK9P0fEaNPag51hXf+Rz88OQW6goAmfvNRIOro=" src="https://assets-cdn.github.com/assets/github-ac033f0062bd3f47c468d3da839d615dff91cfcf0e416ea0a0099fbcd4483aba.js"></script>
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
  </body>
</html>

