<div align="center">
	<p>
		<img alt="Thoughtworks Logo" src="https://raw.githubusercontent.com/ThoughtWorks-DPS/static/master/thoughtworks_flamingo_wave.png?sanitize=true" width=200 />
    <br />
		<img alt="DPS Title" src="https://raw.githubusercontent.com/ThoughtWorks-DPS/static/master/dps_lab_title.png" width=350/>
	</p>
  <h3>orb-1password-connect</h3>
  <h5>a workflow orb for authoring circleci remote-docker images</h5>
  <a href="https://app.circleci.com/pipelines/github/ThoughtWorks-DPS/orb-1password-connect"><img src="https://circleci.com/gh/ThoughtWorks-DPS/orb-1password-connect.svg?style=shield"></a> <a href="https://badges.circleci.com/orbs/twdps/onepassword.svg"><img src="https://badges.circleci.com/orbs/twdps/onepassword.svg"></a> <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
</div>
<br />

See [orb registry](https://circleci.com/developer/orbs/orb/twdps/onepassword) for detailed usage examples

Available options include:

  - install-op: install op cli on current executor
  - install-opw: install opw (for creating/updating secrets) on current executor
  - env: inject standard op .env file, output to $BASH_ENV and source
