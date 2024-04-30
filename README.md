<div align="center">
	<p>
		<img alt="Thoughtworks Logo" src="https://raw.githubusercontent.com/ThoughtWorks-DPS/static/master/thoughtworks_flamingo_wave.png?sanitize=true" width=200 />
    <br />
		<img alt="DPS Title" src="https://raw.githubusercontent.com/ThoughtWorks-DPS/static/master/EMPCPlatformStarterKitsImage.png" width=350/>
	</p>
  <h3>orb-1password</h3>
  <h5>install cli and perform common pipeline tasks</h5>
  <a href="https://app.circleci.com/pipelines/github/ThoughtWorks-DPS/orb-1password"><img src="https://circleci.com/gh/ThoughtWorks-DPS/orb-1password.svg?style=shield"></a> <a href="https://badges.circleci.com/orbs/twdps/onepassword.svg"><img src="https://badges.circleci.com/orbs/twdps/onepassword.svg"></a> <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
</div>
<br />

Orb for using 1password cloud and connect servers in pipelines. See [orb registry](https://circleci.com/developer/orbs/orb/twdps/onepassword) for detailed usage examples.

NOTE: v3.x.x is a breaking change. Review documentation in detail before upgrading.
* Support for the opw (op writer) CLI has been removed
* `package` command renamed to `install`
* `write` command renamed to `write-to-file`
