



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/frameworks-cf3f50c9d690a8f5e3f37bdcac4a6e22275a3954397f954bfaefcec65676e87d.css" integrity="sha256-zz9QydaQqPXj83vcrEpuIidaOVQ5f5VL+u/OxlZ26H0=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-8c445cc0a4a50ab25b19f971f4ae6d4464611129892b42822faf5062651a8208.css" integrity="sha256-jERcwKSlCrJbGflx9K5tRGRhESmJK0KCL69QYmUaggg=" media="all" rel="stylesheet" />
    
    
    
    

    <link as="script" href="https://assets-cdn.github.com/assets/frameworks-952d14ac162c6f6f327175882f6b1a4645bf7aadc9b36ccd52d50fc6f34c8568.js" rel="preload" />
    
    <link as="script" href="https://assets-cdn.github.com/assets/github-29262a1cd0952b4d15fbb6c0991a6e5c2b88f2f19efc3dc7839b326c04759e0a.js" rel="preload" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=device-width">
    
    <title>PracticalMachineLearning/predictionAssignment.md at master · benjamin-chan/PracticalMachineLearning</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="https://avatars1.githubusercontent.com/u/1897044?v=3&amp;s=400" name="twitter:image:src" /><meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="benjamin-chan/PracticalMachineLearning" name="twitter:title" /><meta content="PracticalMachineLearning - Coursera course: Practical Machine Learning" name="twitter:description" />
      <meta content="https://avatars1.githubusercontent.com/u/1897044?v=3&amp;s=400" property="og:image" /><meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="benjamin-chan/PracticalMachineLearning" property="og:title" /><meta content="https://github.com/benjamin-chan/PracticalMachineLearning" property="og:url" /><meta content="PracticalMachineLearning - Coursera course: Practical Machine Learning" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTkzNjgwMTE6M2U2ZjJiNDhmNDEyODc0NDk4OTk2MjBiMzA0ZjZkZGY6ZmJkNTgxYWUwODE2YWFmNDlmZjQ2ZWYxYjQxZDhhZWUxMzZiMzIyOWUzZmEyMDJiZmFiMGI4NTUxZjUwYjliOA==--bc474aa29caf69ac0e6f878e13f52fe259808eff">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
<meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="CA3BE73D:6CA8:EF54FE0:57A47E51" name="octolytics-dimension-request_id" /><meta content="19368011" name="octolytics-actor-id" /><meta content="anuragnagaich" name="octolytics-actor-login" /><meta content="528915d4755387a0f816342d6785e0fcf88df8ce1ec13217dc018c49dec768be" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="anuragnagaich">

        <meta name="expected-hostname" content="github.com">
      <meta name="js-proxy-site-detection-payload" content="NDExNDcyNjg0M2M1MThlZjU0ZGU0MzUyMzhkNDgyMjcwMWU4NDkxMjA2OTYyZDU2NDBmNzlkYTM4NDcxOWU5NHx7InJlbW90ZV9hZGRyZXNzIjoiMjAyLjU5LjIzMS42MSIsInJlcXVlc3RfaWQiOiJDQTNCRTczRDo2Q0E4OkVGNTRGRTA6NTdBNDdFNTEiLCJ0aW1lc3RhbXAiOjE0NzAzOTgwMzR9">


      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta name="html-safe-nonce" content="d12cd1e3efb4189234a88f2f401ece2b9f93c8d6">
    <meta content="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" name="form-nonce" />

    <meta http-equiv="x-pjax-version" content="eb3c3428d1079da201accb2cd431321c">
    

      
  <meta name="description" content="PracticalMachineLearning - Coursera course: Practical Machine Learning">
  <meta name="go-import" content="github.com/benjamin-chan/PracticalMachineLearning git https://github.com/benjamin-chan/PracticalMachineLearning.git">

  <meta content="1897044" name="octolytics-dimension-user_id" /><meta content="benjamin-chan" name="octolytics-dimension-user_login" /><meta content="24853557" name="octolytics-dimension-repository_id" /><meta content="benjamin-chan/PracticalMachineLearning" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="24853557" name="octolytics-dimension-repository_network_root_id" /><meta content="benjamin-chan/PracticalMachineLearning" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/benjamin-chan/PracticalMachineLearning/commits/master.atom" rel="alternate" title="Recent Commits to PracticalMachineLearning:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/benjamin-chan/PracticalMachineLearning/blob/master/predictionAssignment.md" data-pjax-transient>
  </head>


  <body class="logged-in  env-production windows vis-public page-blob">
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"></div>
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg aria-hidden="true" class="octicon octicon-mark-github" height="28" version="1.1" viewBox="0 0 16 16" width="28"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>


        <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/benjamin-chan/PracticalMachineLearning/search" class="js-site-search-form" data-scoped-search-url="/benjamin-chan/PracticalMachineLearning/search" data-unscoped-search-url="/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <label class="form-control header-search-wrapper js-chromeless-input-container">
      <div class="header-search-scope">This repository</div>
      <input type="text"
        class="form-control header-search-input js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s"
        name="q"
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off">
    </label>
</form></div>


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
    

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <svg aria-hidden="true" class="octicon octicon-plus left" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 9H7v5H5V9H0V7h5V2h2v5h5z"></path></svg>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="benjamin-chan/PracticalMachineLearning">This repository</span>
  </div>
    <a class="dropdown-item" href="/benjamin-chan/PracticalMachineLearning/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/anuragnagaich"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@anuragnagaich" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/19368011?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">anuragnagaich</strong>
        </div>

        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/anuragnagaich" data-ga-click="Header, go to profile, text:your profile">
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

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="MOPVql6yXCm64MbAFfaq42sp4LeMiP7LxrcmhfTmB9PdnRaz1YYVmhFPuwcvfsvrnP3wXmtt/Cb9wnhyy5Ym1Q==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>


      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode">
    <div id="js-repo-pjax-container" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="dBSgNdhCBsRlfiupqeoFF0kRU2yaxWq/SRZ06g/K+TEX4UJYPJLfe2DRQbNLxYsdX+Oqq9t2q+1ELNBnh5N+bQ==" /></div>      <input class="form-control" id="repository_id" name="repository_id" type="hidden" value="24853557" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/benjamin-chan/PracticalMachineLearning/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count" href="/benjamin-chan/PracticalMachineLearning/watchers">
            5
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header js-navigation-enable" tabindex="-1">
              <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-eye" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"></path></svg>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <svg aria-hidden="true" class="octicon octicon-mute" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"></path></svg>
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

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/benjamin-chan/PracticalMachineLearning/unstar" class="starred" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="6jQIl2zFdJnd86L3G0yV0PSezZzHvbjEUvAhutwmhZjfbUo/PGxGq65wX6w/6YiKhO2l5JQ2D89NaHBk/KjMvA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar benjamin-chan/PracticalMachineLearning"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/benjamin-chan/PracticalMachineLearning/stargazers">
          7
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/benjamin-chan/PracticalMachineLearning/star" class="unstarred" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="HpQo8YC2PlqNUIxpkT33gMsX7PLU6++y+PxS8ZNFtCC1tB7gVIAh0RLru9mEkT8H5BU3fnQm2e1WsX8JIsSByA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star benjamin-chan/PracticalMachineLearning"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <svg aria-hidden="true" class="octicon octicon-star" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"></path></svg>
        Star
      </button>
        <a class="social-count js-social-count" href="/benjamin-chan/PracticalMachineLearning/stargazers">
          7
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/benjamin-chan/PracticalMachineLearning/fork" class="btn-with-count" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="GACgWTgedCnORt8uQsYiyqz3b3rETLkCqIHs34b5YislaSR1JWy+siWaZwztoUL4kROiqcj85CR/K5ICCkQpdw==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of benjamin-chan/PracticalMachineLearning to your account"
                aria-label="Fork your own copy of benjamin-chan/PracticalMachineLearning to your account">
              <svg aria-hidden="true" class="octicon octicon-repo-forked" height="16" version="1.1" viewBox="0 0 10 16" width="10"><path d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
              Fork
            </button>
</form>
    <a href="/benjamin-chan/PracticalMachineLearning/network" class="social-count">
      48
    </a>
  </li>
</ul>

    <h1 class="public ">
  <svg aria-hidden="true" class="octicon octicon-repo" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"></path></svg>
  <span class="author" itemprop="author"><a href="/benjamin-chan" class="url fn" rel="author">benjamin-chan</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a href="/benjamin-chan/PracticalMachineLearning" data-pjax="#js-repo-pjax-container">PracticalMachineLearning</a></strong>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/benjamin-chan/PracticalMachineLearning" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /benjamin-chan/PracticalMachineLearning" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-code" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"></path></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a href="/benjamin-chan/PracticalMachineLearning/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /benjamin-chan/PracticalMachineLearning/issues" itemprop="url">
        <svg aria-hidden="true" class="octicon octicon-issue-opened" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"></path></svg>
        <span itemprop="name">Issues</span>
        <span class="counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a href="/benjamin-chan/PracticalMachineLearning/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /benjamin-chan/PracticalMachineLearning/pulls" itemprop="url">
      <svg aria-hidden="true" class="octicon octicon-git-pull-request" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg>
      <span itemprop="name">Pull requests</span>
      <span class="counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>

    <a href="/benjamin-chan/PracticalMachineLearning/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /benjamin-chan/PracticalMachineLearning/wiki">
      <svg aria-hidden="true" class="octicon octicon-book" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"></path></svg>
      Wiki
</a>

  <a href="/benjamin-chan/PracticalMachineLearning/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /benjamin-chan/PracticalMachineLearning/pulse">
    <svg aria-hidden="true" class="octicon octicon-pulse" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M11.5 8L8.8 5.4 6.6 8.5 5.5 1.6 2.38 8H0v2h3.6l.9-1.8.9 5.4L9 8.5l1.6 1.5H14V8z"></path></svg>
    Pulse
</a>
  <a href="/benjamin-chan/PracticalMachineLearning/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /benjamin-chan/PracticalMachineLearning/graphs">
    <svg aria-hidden="true" class="octicon octicon-graph" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"></path></svg>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/benjamin-chan/PracticalMachineLearning/blob/f60309ea00885c32bb87d15c057bc87c0af1c101/predictionAssignment.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:61d137859241b603daa6cbb908ccee35 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu branch-select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg aria-label="Close" class="octicon octicon-x js-menu-close" height="16" role="img" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/benjamin-chan/PracticalMachineLearning/blob/Velloso/predictionAssignment.md"
               data-name="Velloso"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="Velloso">
                Velloso
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/benjamin-chan/PracticalMachineLearning/blob/gh-pages/predictionAssignment.md"
               data-name="gh-pages"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="gh-pages">
                gh-pages
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/benjamin-chan/PracticalMachineLearning/blob/master/predictionAssignment.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="master">
                master
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/benjamin-chan/PracticalMachineLearning/blob/test/predictionAssignment.md"
               data-name="test"
               data-skip-pjax="true"
               rel="nofollow">
              <svg aria-hidden="true" class="octicon octicon-check select-menu-item-icon" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"></path></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text" title="test">
                test
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
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
    <a href="/benjamin-chan/PracticalMachineLearning/find/master"
          class="js-pjax-capture-input btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span class="js-path-segment"><a href="/benjamin-chan/PracticalMachineLearning"><span>PracticalMachineLearning</span></a></span></span><span class="separator">/</span><strong class="final-path">predictionAssignment.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/benjamin-chan/PracticalMachineLearning/commit/ffd0eff87333ea5fd475bcc06d7c0a9d4ab20b41" data-pjax>
          ffd0eff
        </a>
        <relative-time datetime="2014-10-23T23:32:48Z">Oct 23, 2014</relative-time>
      </span>
      <div>
        <img alt="@benjamin-chan" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/1897044?v=3&amp;s=40" width="20" />
        <a href="/benjamin-chan" class="user-mention" rel="author">benjamin-chan</a>
          <a href="/benjamin-chan/PracticalMachineLearning/commit/ffd0eff87333ea5fd475bcc06d7c0a9d4ab20b41" class="message" data-pjax="true" title="Add some notes">Add some notes</a>
      </div>

    <div class="commit-tease-contributors">
      <button type="button" class="btn-link muted-link contributors-toggle" data-facebox="#blob_contributors_box">
        <strong>1</strong>
         contributor
      </button>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@benjamin-chan" height="24" src="https://avatars3.githubusercontent.com/u/1897044?v=3&amp;s=48" width="24" />
            <a href="/benjamin-chan">benjamin-chan</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/benjamin-chan/PracticalMachineLearning/raw/master/predictionAssignment.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/benjamin-chan/PracticalMachineLearning/blame/master/predictionAssignment.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/benjamin-chan/PracticalMachineLearning/commits/master/predictionAssignment.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/benjamin-chan/PracticalMachineLearning?branch=master&amp;filepath=predictionAssignment.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <svg aria-hidden="true" class="octicon octicon-device-desktop" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"></path></svg>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/benjamin-chan/PracticalMachineLearning/edit/master/predictionAssignment.md" class="inline-form js-update-url-with-hash" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="aboLJYL1aNLBbA6uNK++cUg6gazfrS3iqxdmDeGg/5Buo8z9xbvl8e24kCSiWLfo7obQZaFk1DJNpYX+hVX8/A==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-pencil" height="16" version="1.1" viewBox="0 0 14 16" width="14"><path d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/benjamin-chan/PracticalMachineLearning/delete/master/predictionAssignment.md" class="inline-form" data-form-nonce="c20406b7487cf93f3c8cb059b6c353a468d7aa1f" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="BGuJZfdMTifYst/aRX+2ZUCgyh5efuhPGvzA+g8pbBLEwdYT9X7qicK+61ZgxTRAZ/sxQvaDKtfBNv1FxldW+A==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <svg aria-hidden="true" class="octicon octicon-trashcan" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"></path></svg>
          </button>
</form>  </div>

  <div class="file-info">
      599 lines (474 sloc)
      <span class="file-info-divider"></span>
    18.9 KB
  </div>
</div>

  
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-coursera-practical-machine-learning-prediction-assignment" class="anchor" href="#coursera-practical-machine-learning-prediction-assignment" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Coursera: Practical Machine Learning Prediction Assignment</h1>

<p>Benjamin Chan <a href="https://github.com/benjamin-chan">GitHub</a>  </p>

<pre><code>## Run time: 2014-10-23 15:40:34
## R version: R version 3.1.1 (2014-07-10)
</code></pre>

<blockquote>
<p><strong>Background</strong></p>

<p>Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: <a href="http://groupware.les.inf.puc-rio.br/har">http://groupware.les.inf.puc-rio.br/har</a> (see the section on the Weight Lifting Exercise Dataset). </p>

<p>*<em>Data *</em></p>

<p>The training data for this project are available here: </p>

<p><a href="https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv">https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv</a></p>

<p>The test data are available here: </p>

<p><a href="https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv">https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv</a></p>

<p>The data for this project come from this source: <a href="http://groupware.les.inf.puc-rio.br/har">http://groupware.les.inf.puc-rio.br/har</a>. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment. </p>

<p><strong>What you should submit</strong></p>

<p>The goal of your project is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. You may use any of the other variables to predict with. You should create a report describing how you built your model, how you used cross validation, what you think the expected out of sample error is, and why you made the choices you did. You will also use your prediction model to predict 20 different test cases. </p>

<ol>
<li>Your submission should consist of a link to a Github repo with your R markdown and compiled HTML file describing your analysis. Please constrain the text of the writeup to &lt; 2000 words and the number of figures to be less than 5. It will make it easier for the graders if you submit a repo with a gh-pages branch so the HTML page can be viewed online (and you always want to make it easy on graders :-).</li>
<li>You should also apply your machine learning algorithm to the 20 test cases available in the test data above. Please submit your predictions in appropriate format to the programming assignment for automated grading. See the programming assignment for additional details. </li>
</ol>

<p>*<em>Reproducibility *</em></p>

<p>Due to security concerns with the exchange of R code, your code will not be run during the evaluation by your classmates. Please be sure that if they download the repo, they will be able to view the compiled HTML version of your analysis. </p>
</blockquote>

<h1><a id="user-content-prepare-the-datasets" class="anchor" href="#prepare-the-datasets" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Prepare the datasets</h1>

<p>Read the training data into a data table.</p>

<div class="highlight highlight-source-r"><pre>require(<span class="pl-smi">data.table</span>)</pre></div>

<pre><code>## Loading required package: data.table
</code></pre>

<div class="highlight highlight-source-r"><pre>setInternet2(<span class="pl-c1">TRUE</span>)
<span class="pl-smi">url</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv<span class="pl-pds">"</span></span>
<span class="pl-smi">D</span> <span class="pl-k">&lt;-</span> fread(<span class="pl-smi">url</span>)</pre></div>

<p>Read the testing data into a data table.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">url</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv<span class="pl-pds">"</span></span>
<span class="pl-smi">DTest</span> <span class="pl-k">&lt;-</span> fread(<span class="pl-smi">url</span>)</pre></div>

<p>Which variables in the test dataset have zero <code>NA</code>s?
Use this tip: <a href="http://stackoverflow.com/a/11330265">finding columns with all missing values in r</a>.</p>

<p>Belt, arm, dumbbell, and forearm variables that do not have any missing values in the test dataset will be <strong>predictor candidates</strong>.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">isAnyMissing</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-smi">DTest</span>, <span class="pl-k">function</span> (<span class="pl-smi">x</span>) any(is.na(<span class="pl-smi">x</span>) <span class="pl-k">|</span> <span class="pl-smi">x</span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>))
<span class="pl-smi">isPredictor</span> <span class="pl-k">&lt;-</span> <span class="pl-k">!</span><span class="pl-smi">isAnyMissing</span> <span class="pl-k">&amp;</span> grepl(<span class="pl-s"><span class="pl-pds">"</span>belt|[^(fore)]arm|dumbbell|forearm<span class="pl-pds">"</span></span>, names(<span class="pl-smi">isAnyMissing</span>))
<span class="pl-smi">predCandidates</span> <span class="pl-k">&lt;-</span> names(<span class="pl-smi">isAnyMissing</span>)[<span class="pl-smi">isPredictor</span>]
<span class="pl-smi">predCandidates</span></pre></div>

<pre><code>##  [1] "roll_belt"            "pitch_belt"           "yaw_belt"            
##  [4] "total_accel_belt"     "gyros_belt_x"         "gyros_belt_y"        
##  [7] "gyros_belt_z"         "accel_belt_x"         "accel_belt_y"        
## [10] "accel_belt_z"         "magnet_belt_x"        "magnet_belt_y"       
## [13] "magnet_belt_z"        "roll_arm"             "pitch_arm"           
## [16] "yaw_arm"              "total_accel_arm"      "gyros_arm_x"         
## [19] "gyros_arm_y"          "gyros_arm_z"          "accel_arm_x"         
## [22] "accel_arm_y"          "accel_arm_z"          "magnet_arm_x"        
## [25] "magnet_arm_y"         "magnet_arm_z"         "roll_dumbbell"       
## [28] "pitch_dumbbell"       "yaw_dumbbell"         "total_accel_dumbbell"
## [31] "gyros_dumbbell_x"     "gyros_dumbbell_y"     "gyros_dumbbell_z"    
## [34] "accel_dumbbell_x"     "accel_dumbbell_y"     "accel_dumbbell_z"    
## [37] "magnet_dumbbell_x"    "magnet_dumbbell_y"    "magnet_dumbbell_z"   
## [40] "roll_forearm"         "pitch_forearm"        "yaw_forearm"         
## [43] "total_accel_forearm"  "gyros_forearm_x"      "gyros_forearm_y"     
## [46] "gyros_forearm_z"      "accel_forearm_x"      "accel_forearm_y"     
## [49] "accel_forearm_z"      "magnet_forearm_x"     "magnet_forearm_y"    
## [52] "magnet_forearm_z"
</code></pre>

<p>Subset the primary dataset to include only the <strong>predictor candidates</strong> and the outcome variable, <code>classe</code>.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">varToInclude</span> <span class="pl-k">&lt;-</span> c(<span class="pl-s"><span class="pl-pds">"</span>classe<span class="pl-pds">"</span></span>, <span class="pl-smi">predCandidates</span>)
<span class="pl-smi">D</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[, <span class="pl-smi">varToInclude</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>]
dim(<span class="pl-smi">D</span>)</pre></div>

<pre><code>## [1] 19622    53
</code></pre>

<div class="highlight highlight-source-r"><pre>names(<span class="pl-smi">D</span>)</pre></div>

<pre><code>##  [1] "classe"               "roll_belt"            "pitch_belt"          
##  [4] "yaw_belt"             "total_accel_belt"     "gyros_belt_x"        
##  [7] "gyros_belt_y"         "gyros_belt_z"         "accel_belt_x"        
## [10] "accel_belt_y"         "accel_belt_z"         "magnet_belt_x"       
## [13] "magnet_belt_y"        "magnet_belt_z"        "roll_arm"            
## [16] "pitch_arm"            "yaw_arm"              "total_accel_arm"     
## [19] "gyros_arm_x"          "gyros_arm_y"          "gyros_arm_z"         
## [22] "accel_arm_x"          "accel_arm_y"          "accel_arm_z"         
## [25] "magnet_arm_x"         "magnet_arm_y"         "magnet_arm_z"        
## [28] "roll_dumbbell"        "pitch_dumbbell"       "yaw_dumbbell"        
## [31] "total_accel_dumbbell" "gyros_dumbbell_x"     "gyros_dumbbell_y"    
## [34] "gyros_dumbbell_z"     "accel_dumbbell_x"     "accel_dumbbell_y"    
## [37] "accel_dumbbell_z"     "magnet_dumbbell_x"    "magnet_dumbbell_y"   
## [40] "magnet_dumbbell_z"    "roll_forearm"         "pitch_forearm"       
## [43] "yaw_forearm"          "total_accel_forearm"  "gyros_forearm_x"     
## [46] "gyros_forearm_y"      "gyros_forearm_z"      "accel_forearm_x"     
## [49] "accel_forearm_y"      "accel_forearm_z"      "magnet_forearm_x"    
## [52] "magnet_forearm_y"     "magnet_forearm_z"
</code></pre>

<p>Make <code>classe</code> into a factor.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">D</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[, <span class="pl-smi">classe</span> <span class="pl-k">:</span><span class="pl-k">=</span> <span class="pl-k">factor</span>(<span class="pl-smi">D</span>[, <span class="pl-smi">classe</span>])]
<span class="pl-smi">D</span>[, .<span class="pl-smi">N</span>, <span class="pl-smi">classe</span>]</pre></div>

<pre><code>##    classe    N
## 1:      A 5580
## 2:      B 3797
## 3:      C 3422
## 4:      D 3216
## 5:      E 3607
</code></pre>

<p>Split the dataset into a 60% training and 40% probing dataset.</p>

<div class="highlight highlight-source-r"><pre>require(<span class="pl-smi">caret</span>)</pre></div>

<pre><code>## Loading required package: caret
## Loading required package: lattice
## Loading required package: ggplot2
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">seed</span> <span class="pl-k">&lt;-</span> as.numeric(as.Date(<span class="pl-s"><span class="pl-pds">"</span>2014-10-26<span class="pl-pds">"</span></span>))
set.seed(<span class="pl-smi">seed</span>)
<span class="pl-smi">inTrain</span> <span class="pl-k">&lt;-</span> createDataPartition(<span class="pl-smi">D</span><span class="pl-k">$</span><span class="pl-smi">classe</span>, <span class="pl-v">p</span><span class="pl-k">=</span><span class="pl-c1">0.6</span>)
<span class="pl-smi">DTrain</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[<span class="pl-smi">inTrain</span>[[<span class="pl-c1">1</span>]]]
<span class="pl-smi">DProbe</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[<span class="pl-k">-</span><span class="pl-smi">inTrain</span>[[<span class="pl-c1">1</span>]]]</pre></div>

<p>Preprocess the prediction variables by centering and scaling.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">X</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">DTrain</span>[, <span class="pl-smi">predCandidates</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>]
<span class="pl-smi">preProc</span> <span class="pl-k">&lt;-</span> preProcess(<span class="pl-smi">X</span>)
<span class="pl-smi">preProc</span></pre></div>

<pre><code>## 
## Call:
## preProcess.default(x = X)
## 
## Created from 11776 samples and 52 variables
## Pre-processing: centered, scaled
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">XCS</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">preProc</span>, <span class="pl-smi">X</span>)
<span class="pl-smi">DTrainCS</span> <span class="pl-k">&lt;-</span> data.table(<span class="pl-k">data.frame</span>(<span class="pl-v">classe</span> <span class="pl-k">=</span> <span class="pl-smi">DTrain</span>[, <span class="pl-smi">classe</span>], <span class="pl-smi">XCS</span>))</pre></div>

<p>Apply the centering and scaling to the probing dataset.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">X</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">DProbe</span>[, <span class="pl-smi">predCandidates</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>]
<span class="pl-smi">XCS</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">preProc</span>, <span class="pl-smi">X</span>)
<span class="pl-smi">DProbeCS</span> <span class="pl-k">&lt;-</span> data.table(<span class="pl-k">data.frame</span>(<span class="pl-v">classe</span> <span class="pl-k">=</span> <span class="pl-smi">DProbe</span>[, <span class="pl-smi">classe</span>], <span class="pl-smi">XCS</span>))</pre></div>

<p>Check for near zero variance.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">nzv</span> <span class="pl-k">&lt;-</span> nearZeroVar(<span class="pl-smi">DTrainCS</span>, <span class="pl-v">saveMetrics</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
<span class="pl-k">if</span> (any(<span class="pl-smi">nzv</span><span class="pl-k">$</span><span class="pl-smi">nzv</span>)) <span class="pl-smi">nzv</span> <span class="pl-k">else</span> message(<span class="pl-s"><span class="pl-pds">"</span>No variables with near zero variance<span class="pl-pds">"</span></span>)</pre></div>

<pre><code>## No variables with near zero variance
</code></pre>

<p>Examine groups of prediction variables.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-en">histGroup</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span> (<span class="pl-smi">data</span>, <span class="pl-smi">regex</span>) {
  <span class="pl-smi">col</span> <span class="pl-k">&lt;-</span> grep(<span class="pl-smi">regex</span>, names(<span class="pl-smi">data</span>))
  <span class="pl-smi">col</span> <span class="pl-k">&lt;-</span> c(<span class="pl-smi">col</span>, which(names(<span class="pl-smi">data</span>) <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">"</span>classe<span class="pl-pds">"</span></span>))
  require(<span class="pl-smi">reshape2</span>)
  <span class="pl-smi">n</span> <span class="pl-k">&lt;-</span> nrow(<span class="pl-smi">data</span>)
  <span class="pl-smi">DMelted</span> <span class="pl-k">&lt;-</span> melt(<span class="pl-smi">data</span>[, <span class="pl-smi">col</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>][, <span class="pl-smi">rownum</span> <span class="pl-k">:</span><span class="pl-k">=</span> seq(<span class="pl-c1">1</span>, <span class="pl-smi">n</span>)], <span class="pl-v">id.vars</span><span class="pl-k">=</span>c(<span class="pl-s"><span class="pl-pds">"</span>rownum<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>classe<span class="pl-pds">"</span></span>))
  require(<span class="pl-smi">ggplot2</span>)
  ggplot(<span class="pl-smi">DMelted</span>, aes(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">classe</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">value</span>)) <span class="pl-k">+</span>
    geom_violin(aes(<span class="pl-v">color</span><span class="pl-k">=</span><span class="pl-smi">classe</span>, <span class="pl-v">fill</span><span class="pl-k">=</span><span class="pl-smi">classe</span>), <span class="pl-v">alpha</span><span class="pl-k">=</span><span class="pl-c1">1</span><span class="pl-k">/</span><span class="pl-c1">2</span>) <span class="pl-k">+</span>
<span class="pl-c">#     geom_jitter(aes(color=classe, fill=classe), alpha=1/10) +</span>
<span class="pl-c">#     geom_smooth(aes(group=1), method="gam", color="black", alpha=1/2, size=2) +</span>
    facet_wrap(<span class="pl-k">~</span> <span class="pl-smi">variable</span>, <span class="pl-v">scale</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>free_y<span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    scale_color_brewer(<span class="pl-v">palette</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Spectral<span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    scale_fill_brewer(<span class="pl-v">palette</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Spectral<span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    labs(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    theme(<span class="pl-v">legend.position</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>none<span class="pl-pds">"</span></span>)
}
histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>belt<span class="pl-pds">"</span></span>)</pre></div>

<pre><code>## Loading required package: reshape2
</code></pre>

<p><a href="/benjamin-chan/PracticalMachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup1.png" target="_blank"><img src="/benjamin-chan/PracticalMachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup1.png" alt="plot of chunk histGroup" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>[^(fore)]arm<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/benjamin-chan/PracticalMachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup2.png" target="_blank"><img src="/benjamin-chan/PracticalMachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup2.png" alt="plot of chunk histGroup" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>dumbbell<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/benjamin-chan/PracticalMachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup3.png" target="_blank"><img src="/benjamin-chan/PracticalMachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup3.png" alt="plot of chunk histGroup" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>forearm<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/benjamin-chan/PracticalMachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup4.png" target="_blank"><img src="/benjamin-chan/PracticalMachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup4.png" alt="plot of chunk histGroup" style="max-width:100%;"></a> </p>

<h1><a id="user-content-train-a-prediction-model" class="anchor" href="#train-a-prediction-model" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Train a prediction model</h1>

<p>Using random forest, the out of sample error should be small.
The error will be estimated using the 40% probing sample.
I would be quite happy with an error estimate of 3% or less.</p>

<p>Set up the parallel clusters.</p>

<div class="highlight highlight-source-r"><pre>require(<span class="pl-smi">parallel</span>)</pre></div>

<pre><code>## Loading required package: parallel
</code></pre>

<div class="highlight highlight-source-r"><pre>require(<span class="pl-smi">doParallel</span>)</pre></div>

<pre><code>## Loading required package: doParallel
## Loading required package: foreach
## Loading required package: iterators
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">cl</span> <span class="pl-k">&lt;-</span> makeCluster(detectCores() <span class="pl-k">-</span> <span class="pl-c1">1</span>)
registerDoParallel(<span class="pl-smi">cl</span>)</pre></div>

<p>Set the control parameters.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">ctrl</span> <span class="pl-k">&lt;-</span> trainControl(<span class="pl-v">classProbs</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>,
                     <span class="pl-v">savePredictions</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>,
                     <span class="pl-v">allowParallel</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)</pre></div>

<p>Fit model over the tuning parameters.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">method</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>rf<span class="pl-pds">"</span></span>
system.time(<span class="pl-smi">trainingModel</span> <span class="pl-k">&lt;-</span> train(<span class="pl-smi">classe</span> <span class="pl-k">~</span> ., <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">DTrainCS</span>, <span class="pl-v">method</span><span class="pl-k">=</span><span class="pl-smi">method</span>))</pre></div>

<pre><code>## Loading required package: randomForest
## randomForest 4.6-10
## Type rfNews() to see new features/changes/bug fixes.
</code></pre>

<pre><code>##    user  system elapsed 
##   50.36    0.18 1482.91
</code></pre>

<p>Stop the clusters.</p>

<div class="highlight highlight-source-r"><pre>stopCluster(<span class="pl-smi">cl</span>)</pre></div>

<h2><a id="user-content-evaluate-the-model-on-the-training-dataset" class="anchor" href="#evaluate-the-model-on-the-training-dataset" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Evaluate the model on the training dataset</h2>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">trainingModel</span></pre></div>

<pre><code>## Random Forest 
## 
## 11776 samples
##    52 predictor
##     5 classes: 'A', 'B', 'C', 'D', 'E' 
## 
## No pre-processing
## Resampling: Bootstrapped (25 reps) 
## 
## Summary of sample sizes: 11776, 11776, 11776, 11776, 11776, 11776, ... 
## 
## Resampling results across tuning parameters:
## 
##   mtry  Accuracy  Kappa  Accuracy SD  Kappa SD
##    2    1         1      0.002        0.002   
##   27    1         1      0.002        0.002   
##   52    1         1      0.004        0.006   
## 
## Accuracy was used to select the optimal model using  the largest value.
## The final value used for the model was mtry = 27.
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">hat</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">trainingModel</span>, <span class="pl-smi">DTrainCS</span>)
confusionMatrix(<span class="pl-smi">hat</span>, <span class="pl-smi">DTrain</span>[, <span class="pl-smi">classe</span>])</pre></div>

<pre><code>## Confusion Matrix and Statistics
## 
##           Reference
## Prediction    A    B    C    D    E
##          A 3348    0    0    0    0
##          B    0 2279    0    0    0
##          C    0    0 2054    0    0
##          D    0    0    0 1930    0
##          E    0    0    0    0 2165
## 
## Overall Statistics
##                                 
##                Accuracy : 1     
##                  95% CI : (1, 1)
##     No Information Rate : 0.284 
##     P-Value [Acc &gt; NIR] : &lt;2e-16
##                                 
##                   Kappa : 1     
##  Mcnemar's Test P-Value : NA    
## 
## Statistics by Class:
## 
##                      Class: A Class: B Class: C Class: D Class: E
## Sensitivity             1.000    1.000    1.000    1.000    1.000
## Specificity             1.000    1.000    1.000    1.000    1.000
## Pos Pred Value          1.000    1.000    1.000    1.000    1.000
## Neg Pred Value          1.000    1.000    1.000    1.000    1.000
## Prevalence              0.284    0.194    0.174    0.164    0.184
## Detection Rate          0.284    0.194    0.174    0.164    0.184
## Detection Prevalence    0.284    0.194    0.174    0.164    0.184
## Balanced Accuracy       1.000    1.000    1.000    1.000    1.000
</code></pre>

<h2><a id="user-content-evaluate-the-model-on-the-probing-dataset" class="anchor" href="#evaluate-the-model-on-the-probing-dataset" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Evaluate the model on the probing dataset</h2>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">hat</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">trainingModel</span>, <span class="pl-smi">DProbeCS</span>)
confusionMatrix(<span class="pl-smi">hat</span>, <span class="pl-smi">DProbeCS</span>[, <span class="pl-smi">classe</span>])</pre></div>

<pre><code>## Confusion Matrix and Statistics
## 
##           Reference
## Prediction    A    B    C    D    E
##          A 2230   16    0    0    0
##          B    1 1498    6    2    2
##          C    0    4 1353   18    7
##          D    0    0    9 1265    7
##          E    1    0    0    1 1426
## 
## Overall Statistics
##                                         
##                Accuracy : 0.991         
##                  95% CI : (0.988, 0.993)
##     No Information Rate : 0.284         
##     P-Value [Acc &gt; NIR] : &lt;2e-16        
##                                         
##                   Kappa : 0.988         
##  Mcnemar's Test P-Value : NA            
## 
## Statistics by Class:
## 
##                      Class: A Class: B Class: C Class: D Class: E
## Sensitivity             0.999    0.987    0.989    0.984    0.989
## Specificity             0.997    0.998    0.996    0.998    1.000
## Pos Pred Value          0.993    0.993    0.979    0.988    0.999
## Neg Pred Value          1.000    0.997    0.998    0.997    0.998
## Prevalence              0.284    0.193    0.174    0.164    0.184
## Detection Rate          0.284    0.191    0.172    0.161    0.182
## Detection Prevalence    0.286    0.192    0.176    0.163    0.182
## Balanced Accuracy       0.998    0.993    0.992    0.991    0.994
</code></pre>

<h2><a id="user-content-display-the-final-model" class="anchor" href="#display-the-final-model" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Display the final model</h2>

<div class="highlight highlight-source-r"><pre>varImp(<span class="pl-smi">trainingModel</span>)</pre></div>

<pre><code>## rf variable importance
## 
##   only 20 most important variables shown (out of 52)
## 
##                      Overall
## roll_belt             100.00
## pitch_forearm          59.81
## yaw_belt               54.35
## pitch_belt             45.92
## magnet_dumbbell_z      43.76
## roll_forearm           43.52
## magnet_dumbbell_y      43.32
## accel_dumbbell_y       22.41
## roll_dumbbell          18.30
## magnet_dumbbell_x      17.99
## accel_forearm_x        17.50
## accel_belt_z           14.59
## magnet_belt_z          14.43
## accel_dumbbell_z       13.94
## magnet_forearm_z       13.91
## total_accel_dumbbell   13.20
## magnet_belt_y          12.33
## yaw_arm                11.81
## gyros_belt_z           11.18
## magnet_belt_x           9.19
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">trainingModel</span><span class="pl-k">$</span><span class="pl-smi">finalModel</span></pre></div>

<pre><code>## 
## Call:
##  randomForest(x = x, y = y, mtry = param$mtry) 
##                Type of random forest: classification
##                      Number of trees: 500
## No. of variables tried at each split: 27
## 
##         OOB estimate of  error rate: 0.79%
## Confusion matrix:
##      A    B    C    D    E class.error
## A 3341    5    2    0    0    0.002091
## B   16 2255    7    1    0    0.010531
## C    0   10 2037    7    0    0.008277
## D    0    1   27 1899    3    0.016062
## E    1    2    2    9 2151    0.006467
</code></pre>

<p><strong>The estimated error rate is less than 1%.</strong></p>

<p>Save training model object for later.</p>

<div class="highlight highlight-source-r"><pre>save(<span class="pl-smi">trainingModel</span>, <span class="pl-v">file</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>trainingModel.RData<span class="pl-pds">"</span></span>)</pre></div>

<h1><a id="user-content-predict-on-the-test-data" class="anchor" href="#predict-on-the-test-data" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Predict on the test data</h1>

<p>Load the training model.</p>

<div class="highlight highlight-source-r"><pre>load(<span class="pl-v">file</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>trainingModel.RData<span class="pl-pds">"</span></span>, <span class="pl-v">verbose</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## Loading objects:
##   trainingModel
</code></pre>

<p>Get predictions and evaluate.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">DTestCS</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">preProc</span>, <span class="pl-smi">DTest</span>[, <span class="pl-smi">predCandidates</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>])
<span class="pl-smi">hat</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">trainingModel</span>, <span class="pl-smi">DTestCS</span>)
<span class="pl-smi">DTest</span> <span class="pl-k">&lt;-</span> cbind(<span class="pl-smi">hat</span> , <span class="pl-smi">DTest</span>)
subset(<span class="pl-smi">DTest</span>, <span class="pl-v">select</span><span class="pl-k">=</span>names(<span class="pl-smi">DTest</span>)[grep(<span class="pl-s"><span class="pl-pds">"</span>belt|[^(fore)]arm|dumbbell|forearm<span class="pl-pds">"</span></span>, names(<span class="pl-smi">DTest</span>), <span class="pl-v">invert</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)])</pre></div>

<pre><code>##     hat V1 user_name raw_timestamp_part_1 raw_timestamp_part_2
##  1:   B  1     pedro           1323095002               868349
##  2:   A  2    jeremy           1322673067               778725
##  3:   B  3    jeremy           1322673075               342967
##  4:   A  4    adelmo           1322832789               560311
##  5:   A  5    eurico           1322489635               814776
##  6:   E  6    jeremy           1322673149               510661
##  7:   D  7    jeremy           1322673128               766645
##  8:   B  8    jeremy           1322673076                54671
##  9:   A  9  carlitos           1323084240               916313
## 10:   A 10   charles           1322837822               384285
## 11:   B 11  carlitos           1323084277                36553
## 12:   C 12    jeremy           1322673101               442731
## 13:   B 13    eurico           1322489661               298656
## 14:   A 14    jeremy           1322673043               178652
## 15:   E 15    jeremy           1322673156               550750
## 16:   E 16    eurico           1322489713               706637
## 17:   A 17     pedro           1323094971               920315
## 18:   B 18  carlitos           1323084285               176314
## 19:   B 19     pedro           1323094999               828379
## 20:   B 20    eurico           1322489658               106658
##       cvtd_timestamp new_window num_window problem_id
##  1: 05/12/2011 14:23         no         74          1
##  2: 30/11/2011 17:11         no        431          2
##  3: 30/11/2011 17:11         no        439          3
##  4: 02/12/2011 13:33         no        194          4
##  5: 28/11/2011 14:13         no        235          5
##  6: 30/11/2011 17:12         no        504          6
##  7: 30/11/2011 17:12         no        485          7
##  8: 30/11/2011 17:11         no        440          8
##  9: 05/12/2011 11:24         no        323          9
## 10: 02/12/2011 14:57         no        664         10
## 11: 05/12/2011 11:24         no        859         11
## 12: 30/11/2011 17:11         no        461         12
## 13: 28/11/2011 14:14         no        257         13
## 14: 30/11/2011 17:10         no        408         14
## 15: 30/11/2011 17:12         no        779         15
## 16: 28/11/2011 14:15         no        302         16
## 17: 05/12/2011 14:22         no         48         17
## 18: 05/12/2011 11:24         no        361         18
## 19: 05/12/2011 14:23         no         72         19
## 20: 28/11/2011 14:14         no        255         20
</code></pre>

<h2><a id="user-content-submission-to-coursera" class="anchor" href="#submission-to-coursera" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Submission to Coursera</h2>

<p>Write submission files to <code>predictionAssignment_files/answers</code>.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-v">pml_write_files</span> <span class="pl-k">=</span> <span class="pl-k">function</span>(<span class="pl-smi">x</span>){
  <span class="pl-v">n</span> <span class="pl-k">=</span> length(<span class="pl-smi">x</span>)
  <span class="pl-smi">path</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>predictionAssignment_files/answers<span class="pl-pds">"</span></span>
  <span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-smi">n</span>){
    <span class="pl-v">filename</span> <span class="pl-k">=</span> paste0(<span class="pl-s"><span class="pl-pds">"</span>problem_id_<span class="pl-pds">"</span></span>,<span class="pl-smi">i</span>,<span class="pl-s"><span class="pl-pds">"</span>.txt<span class="pl-pds">"</span></span>)
    write.table(<span class="pl-smi">x</span>[<span class="pl-smi">i</span>],<span class="pl-v">file</span><span class="pl-k">=</span>file.path(<span class="pl-smi">path</span>, <span class="pl-smi">filename</span>),<span class="pl-v">quote</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>,<span class="pl-v">row.names</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>,<span class="pl-v">col.names</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>)
  }
}
pml_write_files(<span class="pl-smi">hat</span>)</pre></div>
</article>
  </div>

</div>

<button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="hidden">Jump to Line</button>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>


    </div>
  </div>

    </div>

        <div class="container site-footer-container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact GitHub</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage" class="site-footer-mark" title="GitHub">
      <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.08655s from github-fe124-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    

    <div id="ajax-error-message" class="ajax-error-message flash flash-error">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
      </button>
      You can't perform that action at this time.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-lS0UrBYsb28ycXWIL2saRkW/eq3Js2zNUtUPxvNMhWg=" src="https://assets-cdn.github.com/assets/frameworks-952d14ac162c6f6f327175882f6b1a4645bf7aadc9b36ccd52d50fc6f34c8568.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-KSYqHNCVK00V+7bAmRpuXCuI8vGe/D3Hg5sybAR1ngo=" src="https://assets-cdn.github.com/assets/github-29262a1cd0952b4d15fbb6c0991a6e5c2b88f2f19efc3dc7839b326c04759e0a.js"></script>
      
      
      
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <svg aria-hidden="true" class="octicon octicon-alert" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"></path></svg>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg aria-hidden="true" class="octicon octicon-x" height="16" version="1.1" viewBox="0 0 12 16" width="12"><path d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"></path></svg>
    </button>
  </div>
</div>

  </body>
</html>

