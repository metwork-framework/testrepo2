# Changelog

## [Unreleased](https://github.com/metwork-framework/mfext/tree/HEAD)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.9...HEAD)

**Implemented enhancements:**

- add opencv-contrib-python-headless to the python3/scientific layer [\#799](https://github.com/metwork-framework/mfext/issues/799)
- Add ssh support with paramiko [\#793](https://github.com/metwork-framework/mfext/issues/793)

**Closed issues:**

- Add markdown support to sphinx [\#804](https://github.com/metwork-framework/mfext/issues/804)
- Adding python testing packages [\#803](https://github.com/metwork-framework/mfext/issues/803)
- in a python2 plugin\_env on 0.9 branch we have some errors or warnings during make develop [\#801](https://github.com/metwork-framework/mfext/issues/801)
- Upgrade coverage to the latest version \(5.1\) [\#788](https://github.com/metwork-framework/mfext/issues/788)
- interesting library \(to investigate\) [\#787](https://github.com/metwork-framework/mfext/issues/787)
- move python2 stuff in a dedicated addon [\#412](https://github.com/metwork-framework/mfext/issues/412)

**Merged pull requests:**

- build: mfplugin update [\#812](https://github.com/metwork-framework/mfext/pull/812) ([thefab](https://github.com/thefab))
- feat: add python3 devtools components \(pytest-xdist, pytest-mock, fre… [\#810](https://github.com/metwork-framework/mfext/pull/810) ([thebaptiste](https://github.com/thebaptiste))
- build: update mfplugin [\#808](https://github.com/metwork-framework/mfext/pull/808) ([thefab](https://github.com/thefab))
- build: update "internal" python components [\#807](https://github.com/metwork-framework/mfext/pull/807) ([thebaptiste](https://github.com/thebaptiste))
- build: fix components.md [\#806](https://github.com/metwork-framework/mfext/pull/806) ([thebaptiste](https://github.com/thebaptiste))
- Misc changes [\#805](https://github.com/metwork-framework/mfext/pull/805) ([thefab](https://github.com/thefab))
- build: little fix with virtualenv [\#800](https://github.com/metwork-framework/mfext/pull/800) ([thefab](https://github.com/thefab))
- feat: add paramiko \(python implementation of SSHv2\) and dependencies [\#797](https://github.com/metwork-framework/mfext/pull/797) ([thebaptiste](https://github.com/thebaptiste))
- Update components [\#796](https://github.com/metwork-framework/mfext/pull/796) ([thebaptiste](https://github.com/thebaptiste))
- Update components.md [\#795](https://github.com/metwork-framework/mfext/pull/795) ([thefab](https://github.com/thefab))
- build: use a timeout in systemctl start \(just in case...\) [\#791](https://github.com/metwork-framework/mfext/pull/791) ([thefab](https://github.com/thefab))
- build: mfplugin update [\#790](https://github.com/metwork-framework/mfext/pull/790) ([thefab](https://github.com/thefab))
- feat: new plugin system [\#789](https://github.com/metwork-framework/mfext/pull/789) ([thefab](https://github.com/thefab))
- feat: update log\_proxy to version 0.1.0 \(fix a potential deadlock in … [\#786](https://github.com/metwork-framework/mfext/pull/786) ([thebaptiste](https://github.com/thebaptiste))
- feat: add xattrfile from specific Metwork repo \(was before included i… [\#785](https://github.com/metwork-framework/mfext/pull/785) ([thebaptiste](https://github.com/thebaptiste))
- feat: remove all references to MFCOM or mfcom, including backward com… [\#783](https://github.com/metwork-framework/mfext/pull/783) ([thebaptiste](https://github.com/thebaptiste))
- feat: add a new feature in circus\_hooks with special exit code 200 [\#779](https://github.com/metwork-framework/mfext/pull/779) ([thefab](https://github.com/thefab))
- feat: add python3 package 'pika' [\#778](https://github.com/metwork-framework/mfext/pull/778) ([thebaptiste](https://github.com/thebaptiste))
- fix: mfxxx.status must return 1 when errors occur [\#776](https://github.com/metwork-framework/mfext/pull/776) ([thebaptiste](https://github.com/thebaptiste))
- build: add possibility to extract files from a rpm [\#775](https://github.com/metwork-framework/mfext/pull/775) ([thebaptiste](https://github.com/thebaptiste))
- fix: fix compatibility with old systemd versions [\#774](https://github.com/metwork-framework/mfext/pull/774) ([thefab](https://github.com/thefab))
- Plpythonu [\#773](https://github.com/metwork-framework/mfext/pull/773) ([thebaptiste](https://github.com/thebaptiste))
- feat: update mfutil to get explicit error messages in some cases when… [\#772](https://github.com/metwork-framework/mfext/pull/772) ([thebaptiste](https://github.com/thebaptiste))
- build: remove nginx warning in some corner cases [\#771](https://github.com/metwork-framework/mfext/pull/771) ([thefab](https://github.com/thefab))
- build: update components.md [\#766](https://github.com/metwork-framework/mfext/pull/766) ([thebaptiste](https://github.com/thebaptiste))
- build: change nginx default error log \(bp \#664\) [\#764](https://github.com/metwork-framework/mfext/pull/764) ([mergify[bot]](https://github.com/apps/mergify))
- feat: update log\_proxy to fix problem when a maximum file size if set… [\#762](https://github.com/metwork-framework/mfext/pull/762) ([thebaptiste](https://github.com/thebaptiste))
- feat: add fontconfig and freetype \(moved from mfextaddon\_scientific\) [\#761](https://github.com/metwork-framework/mfext/pull/761) ([thebaptiste](https://github.com/thebaptiste))
- \[WIP\] mfextaddon\_python2 [\#760](https://github.com/metwork-framework/mfext/pull/760) ([thebaptiste](https://github.com/thebaptiste))
- build: fix components.md [\#759](https://github.com/metwork-framework/mfext/pull/759) ([thebaptiste](https://github.com/thebaptiste))
- build: upgrade psutil from 5.6.3 to 5.6.6 to fix security issue [\#758](https://github.com/metwork-framework/mfext/pull/758) ([thebaptiste](https://github.com/thebaptiste))
- feat: upgrade netcdf\_c from 4.7.0 to 4.7.3 [\#757](https://github.com/metwork-framework/mfext/pull/757) ([thebaptiste](https://github.com/thebaptiste))
- Misc4 [\#753](https://github.com/metwork-framework/mfext/pull/753) ([thefab](https://github.com/thefab))
- build: automatic mflog configuration [\#752](https://github.com/metwork-framework/mfext/pull/752) ([thefab](https://github.com/thefab))
- feat: mflog update [\#751](https://github.com/metwork-framework/mfext/pull/751) ([thefab](https://github.com/thefab))
- feat: cronwrapper update [\#750](https://github.com/metwork-framework/mfext/pull/750) ([thefab](https://github.com/thefab))
- feat: we can use \*\_CURRENT\_PLUGIN\_\* variables in plugin crontabs [\#749](https://github.com/metwork-framework/mfext/pull/749) ([thefab](https://github.com/thefab))
- build: fix because of SC1117 [\#747](https://github.com/metwork-framework/mfext/pull/747) ([thebaptiste](https://github.com/thebaptiste))
- fix: fix issue 745 \(problem with blank lines while editing crontab\) [\#746](https://github.com/metwork-framework/mfext/pull/746) ([thebaptiste](https://github.com/thebaptiste))
- Remove python2 [\#743](https://github.com/metwork-framework/mfext/pull/743) ([thebaptiste](https://github.com/thebaptiste))
- build: update components.md [\#742](https://github.com/metwork-framework/mfext/pull/742) ([thebaptiste](https://github.com/thebaptiste))
- build: add bjoern \(moved from mfserv\) [\#741](https://github.com/metwork-framework/mfext/pull/741) ([thebaptiste](https://github.com/thebaptiste))
- build: add bjoern \(moved from mfserv\) [\#740](https://github.com/metwork-framework/mfext/pull/740) ([thebaptiste](https://github.com/thebaptiste))
- build: update mfutil [\#739](https://github.com/metwork-framework/mfext/pull/739) ([thebaptiste](https://github.com/thebaptiste))
- build: part2 of metwork-framework/mfserv\#269 [\#738](https://github.com/metwork-framework/mfext/pull/738) ([thefab](https://github.com/thefab))
- build: update components.md [\#737](https://github.com/metwork-framework/mfext/pull/737) ([thebaptiste](https://github.com/thebaptiste))
- Remove python2 [\#736](https://github.com/metwork-framework/mfext/pull/736) ([thebaptiste](https://github.com/thebaptiste))
- Misc3 [\#734](https://github.com/metwork-framework/mfext/pull/734) ([thefab](https://github.com/thefab))
- feat: do not build the layer if file .bypass\_build\_if\_missing contain… [\#733](https://github.com/metwork-framework/mfext/pull/733) ([thebaptiste](https://github.com/thebaptiste))
- build: add pathlib, missing dependency of gitignore-parser in python2 [\#731](https://github.com/metwork-framework/mfext/pull/731) ([thebaptiste](https://github.com/thebaptiste))
- feat: move all python2 stuff out of mfext \(moved in a dedicated mfext… [\#730](https://github.com/metwork-framework/mfext/pull/730) ([thebaptiste](https://github.com/thebaptiste))
- Integration [\#729](https://github.com/metwork-framework/mfext/pull/729) ([thebaptiste](https://github.com/thebaptiste))
- build: update components.md [\#727](https://github.com/metwork-framework/mfext/pull/727) ([thefab](https://github.com/thefab))
- build: little detail [\#726](https://github.com/metwork-framework/mfext/pull/726) ([thefab](https://github.com/thefab))
- build: some work about metwork-framework/mfsysmon\#82 [\#725](https://github.com/metwork-framework/mfext/pull/725) ([thefab](https://github.com/thefab))
- feat: add possibility to exclude files when releasing a plugin and up… [\#724](https://github.com/metwork-framework/mfext/pull/724) ([thebaptiste](https://github.com/thebaptiste))
- feat: update log\_proxy to get dot control files [\#721](https://github.com/metwork-framework/mfext/pull/721) ([thebaptiste](https://github.com/thebaptiste))
- build: fix build [\#719](https://github.com/metwork-framework/mfext/pull/719) ([thefab](https://github.com/thefab))
- Mfsysmon issue82 part2 [\#718](https://github.com/metwork-framework/mfext/pull/718) ([thefab](https://github.com/thefab))
- feat: collect and forward metwork plugin versions [\#717](https://github.com/metwork-framework/mfext/pull/717) ([thefab](https://github.com/thefab))
- feat: increase sysctl net.ipv4.tcp\_max\_syn\_backlog [\#714](https://github.com/metwork-framework/mfext/pull/714) ([thefab](https://github.com/thefab))
- fix: custom sysctl.conf was not applied during startup [\#712](https://github.com/metwork-framework/mfext/pull/712) ([thefab](https://github.com/thefab))
- build: mfutil update [\#710](https://github.com/metwork-framework/mfext/pull/710) ([thefab](https://github.com/thefab))
- feat: remove upload system account by default [\#709](https://github.com/metwork-framework/mfext/pull/709) ([thefab](https://github.com/thefab))
- Mfsysmon issue82 [\#708](https://github.com/metwork-framework/mfext/pull/708) ([thefab](https://github.com/thefab))
- build: update components list [\#707](https://github.com/metwork-framework/mfext/pull/707) ([thefab](https://github.com/thefab))
- build: update mfutil [\#706](https://github.com/metwork-framework/mfext/pull/706) ([thefab](https://github.com/thefab))
- feat: introduce automatic cleaning of tmp directory [\#704](https://github.com/metwork-framework/mfext/pull/704) ([thefab](https://github.com/thefab))
- feat: use LOGPROXY\_LOG\_DIRECTORY env variable for log paths [\#702](https://github.com/metwork-framework/mfext/pull/702) ([thebaptiste](https://github.com/thebaptiste))
- feat: update telegraf component [\#701](https://github.com/metwork-framework/mfext/pull/701) ([thefab](https://github.com/thefab))
- build: fix deploycron repository [\#700](https://github.com/metwork-framework/mfext/pull/700) ([thebaptiste](https://github.com/thebaptiste))
- Experimental [\#699](https://github.com/metwork-framework/mfext/pull/699) ([thebaptiste](https://github.com/thebaptiste))
- build: metwork-mfext-layer-python2\_misc should be obsoleted [\#698](https://github.com/metwork-framework/mfext/pull/698) ([thebaptiste](https://github.com/thebaptiste))
- build: remove a deprecated usage of mfutil [\#696](https://github.com/metwork-framework/mfext/pull/696) ([thefab](https://github.com/thefab))
- feat: better interactive profile for mfext [\#695](https://github.com/metwork-framework/mfext/pull/695) ([thefab](https://github.com/thefab))

## [v0.9.9](https://github.com/metwork-framework/mfext/tree/v0.9.9) (2020-05-07)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.8...v0.9.9)

**Closed issues:**

- mfxxx.status do not always return 1 when errors occur [\#777](https://github.com/metwork-framework/mfext/issues/777)

**Merged pull requests:**

- fix: fix systemctl startup with some circusctl versions [\#792](https://github.com/metwork-framework/mfext/pull/792) ([thefab](https://github.com/thefab))

## [v0.9.8](https://github.com/metwork-framework/mfext/tree/v0.9.8) (2020-03-19)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.7...v0.9.8)

**Merged pull requests:**

- build: fix build [\#770](https://github.com/metwork-framework/mfext/pull/770) ([thefab](https://github.com/thefab))
- fix: fix again a little warning [\#769](https://github.com/metwork-framework/mfext/pull/769) ([thefab](https://github.com/thefab))

## [v0.9.7](https://github.com/metwork-framework/mfext/tree/v0.9.7) (2020-03-19)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.6...v0.9.7)

**Implemented enhancements:**

- \_make\_crontab.sh : add MFSERV\_CURRENT\_PLUGIN\_NAME to the parameters [\#748](https://github.com/metwork-framework/mfext/issues/748)
- Problem with blank lines while editing crontab [\#745](https://github.com/metwork-framework/mfext/issues/745)
- Move freetype and fontconfig builds from addon scientific to mfext [\#479](https://github.com/metwork-framework/mfext/issues/479)

**Closed issues:**

- update mfutil  [\#723](https://github.com/metwork-framework/mfext/issues/723)
- update log\_proxy to get dot control files [\#720](https://github.com/metwork-framework/mfext/issues/720)

**Merged pull requests:**

- build: update components.md [\#767](https://github.com/metwork-framework/mfext/pull/767) ([thebaptiste](https://github.com/thebaptiste))
- feat: upgrade netcdf\_c from 4.7.0 to 4.7.3 [\#765](https://github.com/metwork-framework/mfext/pull/765) ([thefab](https://github.com/thefab))
- feat: cronwrapper update to fix uid collisions when mfserv is launche… [\#763](https://github.com/metwork-framework/mfext/pull/763) ([thefab](https://github.com/thefab))

## [v0.9.6](https://github.com/metwork-framework/mfext/tree/v0.9.6) (2020-02-14)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.5...v0.9.6)

**Implemented enhancements:**

- add automatic cleaning of tmp directory [\#703](https://github.com/metwork-framework/mfext/issues/703)
- update mfutil version [\#697](https://github.com/metwork-framework/mfext/issues/697)
- python3 access [\#688](https://github.com/metwork-framework/mfext/issues/688)
- Build all Metwork modules with scl devtoolset-8 [\#663](https://github.com/metwork-framework/mfext/issues/663)
- Drop layer9\_pythonX\_misc layers [\#638](https://github.com/metwork-framework/mfext/issues/638)
- block core dump in metwork profiles [\#515](https://github.com/metwork-framework/mfext/issues/515)

**Fixed bugs:**

- custom sysctl.conf is not applied during startup [\#711](https://github.com/metwork-framework/mfext/issues/711)
- pip usage broken in plugin\_env [\#685](https://github.com/metwork-framework/mfext/issues/685)
- change about core dumps breaks integration tests: [\#684](https://github.com/metwork-framework/mfext/issues/684)
- nasty warning on the welcome banner when you enter a mfdata plugin\_env \(with admin\_hostname != null\) [\#671](https://github.com/metwork-framework/mfext/issues/671)

**Closed issues:**

- mfutil update [\#705](https://github.com/metwork-framework/mfext/issues/705)
- Extra daemon [\#690](https://github.com/metwork-framework/mfext/issues/690)
- cronwrap.sh should load /etc/metwork.custom\_profile and/or ~/.metwork.custom\_profile [\#662](https://github.com/metwork-framework/mfext/issues/662)
- try to change nginx default error log \(at build time\) [\#643](https://github.com/metwork-framework/mfext/issues/643)
- Define how and when mfextaddons are built [\#284](https://github.com/metwork-framework/mfext/issues/284)

**Merged pull requests:**

- feat: increase sysctl net.ipv4.tcp\_max\_syn\_backlog \(bp \#714\) [\#716](https://github.com/metwork-framework/mfext/pull/716) ([mergify[bot]](https://github.com/apps/mergify))
- fix: custom sysctl.conf was not applied during startup [\#715](https://github.com/metwork-framework/mfext/pull/715) ([thefab](https://github.com/thefab))
- fix: fix pip usage inside plugin\_env \(and change cwd for plugin\_home\) \(bp \#686\) [\#687](https://github.com/metwork-framework/mfext/pull/687) ([mergify[bot]](https://github.com/apps/mergify))
- feat: cronwrap load custom profiles like bashrc/profile [\#680](https://github.com/metwork-framework/mfext/pull/680) ([thefab](https://github.com/thefab))

## [v0.9.5](https://github.com/metwork-framework/mfext/tree/v0.9.5) (2020-01-24)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.4...v0.9.5)

**Implemented enhancements:**

- set TMPDIR [\#630](https://github.com/metwork-framework/mfext/issues/630)
- Check built-in system modules are at least at CentOS 8 level [\#572](https://github.com/metwork-framework/mfext/issues/572)
- the doc about new \*misc@mfext layers is missing [\#542](https://github.com/metwork-framework/mfext/issues/542)

**Closed issues:**

- default mfsysmon admin/hostname config to localhost [\#634](https://github.com/metwork-framework/mfext/issues/634)
- old plugins migration [\#627](https://github.com/metwork-framework/mfext/issues/627)

**Merged pull requests:**

- fix: fix nasty warning in mfdata plugin\_env when admin is set [\#675](https://github.com/metwork-framework/mfext/pull/675) ([thefab](https://github.com/thefab))
- fix: fix automatic restart [\#668](https://github.com/metwork-framework/mfext/pull/668) ([thefab](https://github.com/thefab))
- fix: remove some old aliases for vim in python2\_devtools \(bp \#635\) [\#636](https://github.com/metwork-framework/mfext/pull/636) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.9.4](https://github.com/metwork-framework/mfext/tree/v0.9.4) (2020-01-02)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.3...v0.9.4)

**Merged pull requests:**

- build: better plugin\_env fix \(bp \#623\) [\#624](https://github.com/metwork-framework/mfext/pull/624) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.9.3](https://github.com/metwork-framework/mfext/tree/v0.9.3) (2020-01-02)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.2...v0.9.3)

**Implemented enhancements:**

- drop misc@mfext layer [\#565](https://github.com/metwork-framework/mfext/issues/565)
- telegraf support for plugins [\#564](https://github.com/metwork-framework/mfext/issues/564)
- mfserv\_wrapper should load ~mfserv/.bashrc and not /opt/metwork-mfserv/share/profile? [\#560](https://github.com/metwork-framework/mfext/issues/560)
- add wrk2 in devtools@mfext layer [\#555](https://github.com/metwork-framework/mfext/issues/555)

**Closed issues:**

- Add possibility to install pypi modules with SCLs [\#584](https://github.com/metwork-framework/mfext/issues/584)
- configurable and better log rotation [\#571](https://github.com/metwork-framework/mfext/issues/571)

**Merged pull requests:**

- fix: fix plugin\_env behaviour in some corner cases \(bp \#621\) [\#622](https://github.com/metwork-framework/mfext/pull/622) ([mergify[bot]](https://github.com/apps/mergify))
- feat: update circus\_autorestart\_plugin \(bp \#619\) [\#620](https://github.com/metwork-framework/mfext/pull/620) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.9.2](https://github.com/metwork-framework/mfext/tree/v0.9.2) (2019-11-01)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.1...v0.9.2)

**Implemented enhancements:**

- add a more clear warning during plugin "make develop" or "plugins.install" if the module is not initialized [\#549](https://github.com/metwork-framework/mfext/issues/549)
- better interactive/GUI processes detection? [\#544](https://github.com/metwork-framework/mfext/issues/544)
- add a warning message if you activate monitoring in a module and monitoring@mfext is not installed [\#541](https://github.com/metwork-framework/mfext/issues/541)
- systemd service improvements [\#536](https://github.com/metwork-framework/mfext/issues/536)

**Closed issues:**

- one error message in a centos7 container [\#553](https://github.com/metwork-framework/mfext/issues/553)

**Merged pull requests:**

- Backport536 [\#557](https://github.com/metwork-framework/mfext/pull/557) ([thefab](https://github.com/thefab))
- fix: fix metwork services start for systems where /sys is readonly \(bp \#532\) [\#554](https://github.com/metwork-framework/mfext/pull/554) ([mergify[bot]](https://github.com/apps/mergify))
- feat: add a clear warning... \(bp \#550\) [\#551](https://github.com/metwork-framework/mfext/pull/551) ([mergify[bot]](https://github.com/apps/mergify))
- feat: better interactive/GUI processes detection \(bp \#545\) [\#547](https://github.com/metwork-framework/mfext/pull/547) ([mergify[bot]](https://github.com/apps/mergify))
- feat: add a banner about configured mfadmin module \(bp \#543\) [\#546](https://github.com/metwork-framework/mfext/pull/546) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.9.1](https://github.com/metwork-framework/mfext/tree/v0.9.1) (2019-10-23)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.9.0...v0.9.1)

**Merged pull requests:**

- build: fix typo [\#539](https://github.com/metwork-framework/mfext/pull/539) ([thefab](https://github.com/thefab))

## [v0.9.0](https://github.com/metwork-framework/mfext/tree/v0.9.0) (2019-10-22)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.8.5...v0.9.0)

**Fixed bugs:**

- systemd issue with centos8 [\#535](https://github.com/metwork-framework/mfext/issues/535)

**Merged pull requests:**

- fix: fix systemd service \(bp \#537\) [\#538](https://github.com/metwork-framework/mfext/pull/538) ([mergify[bot]](https://github.com/apps/mergify))
- fix: external\_plugins/ directory for mfbase [\#530](https://github.com/metwork-framework/mfext/pull/530) ([thefab](https://github.com/thefab))
- build: update circus version [\#529](https://github.com/metwork-framework/mfext/pull/529) ([thefab](https://github.com/thefab))
- feat: add some layerapi2 functions in mfutil [\#527](https://github.com/metwork-framework/mfext/pull/527) ([thefab](https://github.com/thefab))
- fix: fix dead link to plugins guide [\#526](https://github.com/metwork-framework/mfext/pull/526) ([thebaptiste](https://github.com/thebaptiste))
- build: fix components.md [\#525](https://github.com/metwork-framework/mfext/pull/525) ([thebaptiste](https://github.com/thebaptiste))
- feat: add wrk tool to devtools layer [\#524](https://github.com/metwork-framework/mfext/pull/524) ([thebaptiste](https://github.com/thebaptiste))
- feat: add wrk tool to devtools layer [\#523](https://github.com/metwork-framework/mfext/pull/523) ([thebaptiste](https://github.com/thebaptiste))
- fix: don't write empty requirements{2,3}.txt file in case of errors [\#521](https://github.com/metwork-framework/mfext/pull/521) ([thefab](https://github.com/thefab))
- build: remove update available message [\#518](https://github.com/metwork-framework/mfext/pull/518) ([thefab](https://github.com/thefab))
- Misc refactor [\#517](https://github.com/metwork-framework/mfext/pull/517) ([thefab](https://github.com/thefab))
- feat: infinite circus max\_retry [\#516](https://github.com/metwork-framework/mfext/pull/516) ([thefab](https://github.com/thefab))
- Misc changes [\#513](https://github.com/metwork-framework/mfext/pull/513) ([thefab](https://github.com/thefab))
- build: disable trace in cairo build \(to fix python issue with matplot… [\#512](https://github.com/metwork-framework/mfext/pull/512) ([thebaptiste](https://github.com/thebaptiste))
- build: fix rpm packaging \(conflict with /etc/security/limits.d/50-met… [\#511](https://github.com/metwork-framework/mfext/pull/511) ([thefab](https://github.com/thefab))
- build: obsoletes mfcom layers [\#510](https://github.com/metwork-framework/mfext/pull/510) ([thefab](https://github.com/thefab))
- feat: integrate mfcom in mfext as 3 mfext layers \(misc, python2\_misc … [\#509](https://github.com/metwork-framework/mfext/pull/509) ([thebaptiste](https://github.com/thebaptiste))
- feat: update layerapi2 [\#508](https://github.com/metwork-framework/mfext/pull/508) ([thefab](https://github.com/thefab))
- Update README.md [\#507](https://github.com/metwork-framework/mfext/pull/507) ([lperez31](https://github.com/lperez31))
- build: fix components list [\#506](https://github.com/metwork-framework/mfext/pull/506) ([thefab](https://github.com/thefab))
- Update README.md [\#504](https://github.com/metwork-framework/mfext/pull/504) ([thefab](https://github.com/thefab))
- build: fix root layer drop [\#503](https://github.com/metwork-framework/mfext/pull/503) ([thefab](https://github.com/thefab))
- feat: add hmac openresty component [\#501](https://github.com/metwork-framework/mfext/pull/501) ([thefab](https://github.com/thefab))
- build: remove dummy root layer [\#500](https://github.com/metwork-framework/mfext/pull/500) ([thefab](https://github.com/thefab))
- feat: add black python component [\#499](https://github.com/metwork-framework/mfext/pull/499) ([thefab](https://github.com/thefab))
- chore: update mflog version [\#498](https://github.com/metwork-framework/mfext/pull/498) ([thebaptiste](https://github.com/thebaptiste))
- feat: introduce components utility [\#495](https://github.com/metwork-framework/mfext/pull/495) ([thefab](https://github.com/thefab))
- build: fix systemd behaviour during uninstall [\#493](https://github.com/metwork-framework/mfext/pull/493) ([thefab](https://github.com/thefab))
- feat: replace MODULE\* environment variables names by MFMODULE\* \(MODUL… [\#490](https://github.com/metwork-framework/mfext/pull/490) ([thebaptiste](https://github.com/thebaptiste))
- Integration [\#489](https://github.com/metwork-framework/mfext/pull/489) ([thebaptiste](https://github.com/thebaptiste))
- build: fix integration tests on centos6 [\#488](https://github.com/metwork-framework/mfext/pull/488) ([thefab](https://github.com/thefab))
- build: fix gdal build to use built-in libpng [\#486](https://github.com/metwork-framework/mfext/pull/486) ([thebaptiste](https://github.com/thebaptiste))
- feat: no more default passwords, prelimininary systemd support [\#485](https://github.com/metwork-framework/mfext/pull/485) ([thefab](https://github.com/thefab))
- build: better doc build [\#483](https://github.com/metwork-framework/mfext/pull/483) ([thefab](https://github.com/thefab))
- build: fix system dependency for generic builds [\#482](https://github.com/metwork-framework/mfext/pull/482) ([thefab](https://github.com/thefab))
- build: some doc generation improvements [\#481](https://github.com/metwork-framework/mfext/pull/481) ([thefab](https://github.com/thefab))
- build: preparing shared doc conf from resources [\#480](https://github.com/metwork-framework/mfext/pull/480) ([thefab](https://github.com/thefab))
- feat: add some system dependencies [\#478](https://github.com/metwork-framework/mfext/pull/478) ([thefab](https://github.com/thefab))
- build: improve generic builds [\#477](https://github.com/metwork-framework/mfext/pull/477) ([thefab](https://github.com/thefab))
- build: better components list [\#476](https://github.com/metwork-framework/mfext/pull/476) ([thefab](https://github.com/thefab))
- build: try to add a component list to README [\#475](https://github.com/metwork-framework/mfext/pull/475) ([thefab](https://github.com/thefab))
- doc: better doc [\#474](https://github.com/metwork-framework/mfext/pull/474) ([thefab](https://github.com/thefab))
- chore: suspicious dependencies and system extra dependencies tests ar… [\#472](https://github.com/metwork-framework/mfext/pull/472) ([thebaptiste](https://github.com/thebaptiste))
- build: fix a dependency of the full package [\#471](https://github.com/metwork-framework/mfext/pull/471) ([thefab](https://github.com/thefab))
- build: fix packaging [\#470](https://github.com/metwork-framework/mfext/pull/470) ([thefab](https://github.com/thefab))
- doc: remove duplicate reference documentation [\#469](https://github.com/metwork-framework/mfext/pull/469) ([thefab](https://github.com/thefab))
- some work for the upcoming generic build [\#468](https://github.com/metwork-framework/mfext/pull/468) ([thefab](https://github.com/thefab))
- build: better mrproper target \(for addons\) [\#467](https://github.com/metwork-framework/mfext/pull/467) ([thefab](https://github.com/thefab))
- build: add missing pixman dependency since we removed pango [\#466](https://github.com/metwork-framework/mfext/pull/466) ([thebaptiste](https://github.com/thebaptiste))
- build: add a system dependency for tcl/tk [\#465](https://github.com/metwork-framework/mfext/pull/465) ([thefab](https://github.com/thefab))
- build: fix build with embedded readline and without system readline-d… [\#464](https://github.com/metwork-framework/mfext/pull/464) ([thebaptiste](https://github.com/thebaptiste))
- build: fix build target [\#463](https://github.com/metwork-framework/mfext/pull/463) ([thebaptiste](https://github.com/thebaptiste))
- build: remove useless system dependencies [\#462](https://github.com/metwork-framework/mfext/pull/462) ([thebaptiste](https://github.com/thebaptiste))
- feat: refactoring about \#437, \#432, \#420 [\#461](https://github.com/metwork-framework/mfext/pull/461) ([thefab](https://github.com/thefab))
- doc: Update README.md [\#460](https://github.com/metwork-framework/mfext/pull/460) ([thefab](https://github.com/thefab))
- build: activate test on system extra dependencies \(the build fails if… [\#459](https://github.com/metwork-framework/mfext/pull/459) ([thebaptiste](https://github.com/thebaptiste))
-  feat: embed tcl/tk libraries and build python2/3 with them [\#457](https://github.com/metwork-framework/mfext/pull/457) ([thebaptiste](https://github.com/thebaptiste))
- Remove system dependencies libgfortran, libgfortran4 and libpng12 [\#455](https://github.com/metwork-framework/mfext/pull/455) ([thebaptiste](https://github.com/thebaptiste))
-  feat: embed readline and use it instead of the system library  [\#453](https://github.com/metwork-framework/mfext/pull/453) ([thebaptiste](https://github.com/thebaptiste))
- fix: fix issue \#35 on addon scientific \(build problem with python2 ESMF\) [\#452](https://github.com/metwork-framework/mfext/pull/452) ([thebaptiste](https://github.com/thebaptiste))
- doc: fix doc build \(again\) [\#451](https://github.com/metwork-framework/mfext/pull/451) ([thefab](https://github.com/thefab))
- doc: doc fix [\#449](https://github.com/metwork-framework/mfext/pull/449) ([thefab](https://github.com/thefab))
- fix: use vi in python2 mode when we are in python2 [\#448](https://github.com/metwork-framework/mfext/pull/448) ([thefab](https://github.com/thefab))
- build: fix rpm update issue with new packaging [\#447](https://github.com/metwork-framework/mfext/pull/447) ([thefab](https://github.com/thefab))
- fix: fix vi usage without devtools [\#444](https://github.com/metwork-framework/mfext/pull/444) ([thefab](https://github.com/thefab))
- doc: readme update [\#442](https://github.com/metwork-framework/mfext/pull/442) ([thefab](https://github.com/thefab))
- feat: embed libffi and use it instead of system library [\#441](https://github.com/metwork-framework/mfext/pull/441) ([thebaptiste](https://github.com/thebaptiste))

## [v0.8.5](https://github.com/metwork-framework/mfext/tree/v0.8.5) (2019-10-19)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.8.4...v0.8.5)

**Implemented enhancements:**

- add wrk tool to devtools layer [\#522](https://github.com/metwork-framework/mfext/issues/522)

**Closed issues:**

- don't write requirements{2,3}.txt file in case of errors during virtualenv build [\#520](https://github.com/metwork-framework/mfext/issues/520)

**Merged pull requests:**

- build: fix backport 0.8 [\#533](https://github.com/metwork-framework/mfext/pull/533) ([thebaptiste](https://github.com/thebaptiste))
- fix: external\_plugins/ directory for mfbase \(bp \#530\) [\#531](https://github.com/metwork-framework/mfext/pull/531) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.8.4](https://github.com/metwork-framework/mfext/tree/v0.8.4) (2019-10-15)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.8.3...v0.8.4)

**Merged pull requests:**

- build: remove update available message \(bp \#518\) [\#519](https://github.com/metwork-framework/mfext/pull/519) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.8.3](https://github.com/metwork-framework/mfext/tree/v0.8.3) (2019-09-24)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.8.2...v0.8.3)

**Implemented enhancements:**

- obsolete root layer in packaging [\#484](https://github.com/metwork-framework/mfext/issues/484)

**Merged pull requests:**

- feat: add hmac openresty component \(bp \#501\) [\#502](https://github.com/metwork-framework/mfext/pull/502) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.8.2](https://github.com/metwork-framework/mfext/tree/v0.8.2) (2019-09-21)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.8.1...v0.8.2)

**Implemented enhancements:**

- \_yaml\_to\_md.py ALL need to exclude addons for mfext build [\#487](https://github.com/metwork-framework/mfext/issues/487)
- define acceptable system dependencies for mfext and add an integration test to enforce them [\#436](https://github.com/metwork-framework/mfext/issues/436)
- layerapi2 should be an independant project [\#40](https://github.com/metwork-framework/mfext/issues/40)

**Closed issues:**

- it should be possible to move pcre, glib2, layerapi2, mfutil\_c into core layer [\#437](https://github.com/metwork-framework/mfext/issues/437)
- we should drop most of the "wrappers" directory with layer build dependencies [\#432](https://github.com/metwork-framework/mfext/issues/432)
- move extra devtools in a dedicated addon [\#420](https://github.com/metwork-framework/mfext/issues/420)

**Merged pull requests:**

- feat: introduce components utility [\#497](https://github.com/metwork-framework/mfext/pull/497) ([thefab](https://github.com/thefab))
- fix: use vi in python2 mode when we are in python2 \(bp \#448\) [\#450](https://github.com/metwork-framework/mfext/pull/450) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.8.1](https://github.com/metwork-framework/mfext/tree/v0.8.1) (2019-08-22)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.8.0...v0.8.1)

**Implemented enhancements:**

- add libpixman in scientific\_core layer [\#407](https://github.com/metwork-framework/mfext/issues/407)

**Fixed bugs:**

- update issue with integration branch since new packaging [\#446](https://github.com/metwork-framework/mfext/issues/446)
- vi without devtools hangs with integration branch [\#443](https://github.com/metwork-framework/mfext/issues/443)

**Merged pull requests:**

- fix: fix vi usage without devtools \(bp \#444\) [\#445](https://github.com/metwork-framework/mfext/pull/445) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.8.0](https://github.com/metwork-framework/mfext/tree/v0.8.0) (2019-08-19)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.7.2...v0.8.0)

**Implemented enhancements:**

- use layer dependencies to provide a better build cache [\#12](https://github.com/metwork-framework/mfext/issues/12)

**Merged pull requests:**

- Update \_vim\_wrapper.sh \(bp \#428\) [\#430](https://github.com/metwork-framework/mfext/pull/430) ([mergify[bot]](https://github.com/apps/mergify))
- build: cache path fix \(bp \#425\) [\#426](https://github.com/metwork-framework/mfext/pull/426) ([mergify[bot]](https://github.com/apps/mergify))
- build: little fix about mfutil\_c migration from mfcom to mfext [\#424](https://github.com/metwork-framework/mfext/pull/424) ([thefab](https://github.com/thefab))
- build: fix mfutil location since mfext migration [\#423](https://github.com/metwork-framework/mfext/pull/423) ([thefab](https://github.com/thefab))
- build: use rpath for mfutil\_c [\#422](https://github.com/metwork-framework/mfext/pull/422) ([thefab](https://github.com/thefab))
- doc: better readme [\#421](https://github.com/metwork-framework/mfext/pull/421) ([thefab](https://github.com/thefab))
- build: fix build with python2 [\#419](https://github.com/metwork-framework/mfext/pull/419) ([thefab](https://github.com/thefab))
- build: fix some weird python compilation issues in scientific addon [\#418](https://github.com/metwork-framework/mfext/pull/418) ([thefab](https://github.com/thefab))
- build: ignore plugin files in dhash [\#417](https://github.com/metwork-framework/mfext/pull/417) ([thefab](https://github.com/thefab))
- feat: update mfutil\_c and introduce mfutil\_lua [\#415](https://github.com/metwork-framework/mfext/pull/415) ([thefab](https://github.com/thefab))
- build: new build cache and adm/adm2 merge [\#413](https://github.com/metwork-framework/mfext/pull/413) ([thefab](https://github.com/thefab))
- feat: mflog update to support non standard logging levels [\#410](https://github.com/metwork-framework/mfext/pull/410) ([thefab](https://github.com/thefab))
- test: add a suspicious dependencies test [\#409](https://github.com/metwork-framework/mfext/pull/409) ([thefab](https://github.com/thefab))
- feat: add revert\_ldd.sh and external\_dependencies.sh utilities [\#408](https://github.com/metwork-framework/mfext/pull/408) ([thefab](https://github.com/thefab))
- fix: plugin\_env issue with python2 plugins [\#404](https://github.com/metwork-framework/mfext/pull/404) ([thefab](https://github.com/thefab))
- feat: upgrade redis from 3 to 5 [\#402](https://github.com/metwork-framework/mfext/pull/402) ([thebaptiste](https://github.com/thebaptiste))
- feat: nodejs/npm update \(nodejs 8.11.2 =\> 10.16.0, npm/6.1 =\> npm/6.9\) [\#401](https://github.com/metwork-framework/mfext/pull/401) ([thefab](https://github.com/thefab))
- feat: telegraf update \(1.10.2 =\> 1.11.2\) [\#400](https://github.com/metwork-framework/mfext/pull/400) ([thefab](https://github.com/thefab))
- chore: add configure\_cmake3 to use cmake3 instead of cmake if needed [\#399](https://github.com/metwork-framework/mfext/pull/399) ([thebaptiste](https://github.com/thebaptiste))
- docs: Update MFEXT documentation [\#397](https://github.com/metwork-framework/mfext/pull/397) ([dearith](https://github.com/dearith))
- chore: we can now tmp block mfxxx.autorestart feature with a file [\#396](https://github.com/metwork-framework/mfext/pull/396) ([thefab](https://github.com/thefab))
- docs: fix typo [\#395](https://github.com/metwork-framework/mfext/pull/395) ([dearith](https://github.com/dearith))
- docs: fix typo [\#394](https://github.com/metwork-framework/mfext/pull/394) ([dearith](https://github.com/dearith))
- build: change download link [\#393](https://github.com/metwork-framework/mfext/pull/393) ([thefab](https://github.com/thefab))
- vim config change [\#391](https://github.com/metwork-framework/mfext/pull/391) ([thebaptiste](https://github.com/thebaptiste))
- feat: give up modules start if precondition failed [\#390](https://github.com/metwork-framework/mfext/pull/390) ([thefab](https://github.com/thefab))
- feat: upgrade python3 from 3.5.6 to 3.7.3, python2 from 2.7.15 to 2.7… [\#389](https://github.com/metwork-framework/mfext/pull/389) ([thebaptiste](https://github.com/thebaptiste))
- fix: disable SSE4.2 optimizations to avoid nginx crashing on old servers [\#385](https://github.com/metwork-framework/mfext/pull/385) ([thefab](https://github.com/thefab))
- fix: add pycodestyle \(missing dependency for autopep8\) [\#377](https://github.com/metwork-framework/mfext/pull/377) ([thebaptiste](https://github.com/thebaptiste))
- fix: add pycodestyle \(missing dependency for autopep8\) [\#376](https://github.com/metwork-framework/mfext/pull/376) ([thebaptiste](https://github.com/thebaptiste))
- docs: generate automatically changelogs entries in changelogs.rst file [\#375](https://github.com/metwork-framework/mfext/pull/375) ([dearith](https://github.com/dearith))
- feat: update cookiecutter\_hooks \(reduce multi blank lines to a single… [\#374](https://github.com/metwork-framework/mfext/pull/374) ([thebaptiste](https://github.com/thebaptiste))
- feat: upgrade envtpl \(both in python requirements and under portable\_… [\#371](https://github.com/metwork-framework/mfext/pull/371) ([thebaptiste](https://github.com/thebaptiste))
- Fix vim wrapper with git editor [\#369](https://github.com/metwork-framework/mfext/pull/369) ([thefab](https://github.com/thefab))
- build: update jsonlog2elasticsearch [\#366](https://github.com/metwork-framework/mfext/pull/366) ([thefab](https://github.com/thefab))
- fix: close mflog issue11 [\#362](https://github.com/metwork-framework/mfext/pull/362) ([thefab](https://github.com/thefab))

## [v0.7.2](https://github.com/metwork-framework/mfext/tree/v0.7.2) (2019-08-06)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.7.1...v0.7.2)

**Implemented enhancements:**

- pyzmq \< 17 should not be in python3@mfext layer [\#191](https://github.com/metwork-framework/mfext/issues/191)
- upgrade redis to redis5 [\#47](https://github.com/metwork-framework/mfext/issues/47)

**Fixed bugs:**

- plugin\_env seems to reload python3 layers even if the plugin depends on python2 [\#403](https://github.com/metwork-framework/mfext/issues/403)

**Closed issues:**

- Find a way to use cache for mfextaddons [\#266](https://github.com/metwork-framework/mfext/issues/266)

**Merged pull requests:**

- Backport410 [\#414](https://github.com/metwork-framework/mfext/pull/414) ([thefab](https://github.com/thefab))
- fix: plugin\_env issue with python2 plugins \(bp \#404\) [\#405](https://github.com/metwork-framework/mfext/pull/405) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.7.1](https://github.com/metwork-framework/mfext/tree/v0.7.1) (2019-06-27)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.7.0...v0.7.1)

**Implemented enhancements:**

- add autopep8 for plugin bootstrap ? [\#372](https://github.com/metwork-framework/mfext/issues/372)

**Fixed bugs:**

- nginx build requires a CPU with SSE 4.2 [\#384](https://github.com/metwork-framework/mfext/issues/384)

**Merged pull requests:**

- feat: give up modules start if precondition failed \(bp \#390\) [\#392](https://github.com/metwork-framework/mfext/pull/392) ([mergify[bot]](https://github.com/apps/mergify))
- fix: disable SSE4.2 optimizations to avoid nginx crashing on old servers \(bp \#385\) [\#386](https://github.com/metwork-framework/mfext/pull/386) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.7.0](https://github.com/metwork-framework/mfext/tree/v0.7.0) (2019-05-29)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.6.3...v0.7.0)

**Merged pull requests:**

- Fix vim wrapper with git editor \(bp \#369\) [\#370](https://github.com/metwork-framework/mfext/pull/370) ([mergify[bot]](https://github.com/apps/mergify))
- build: update jsonlog2elasticsearch \(bp \#366\) [\#367](https://github.com/metwork-framework/mfext/pull/367) ([mergify[bot]](https://github.com/apps/mergify))
- fix: close mflog issue11 \(bp \#362\) [\#364](https://github.com/metwork-framework/mfext/pull/364) ([mergify[bot]](https://github.com/apps/mergify))
- Aliasesfix [\#361](https://github.com/metwork-framework/mfext/pull/361) ([thefab](https://github.com/thefab))
- build: fix gitignore [\#360](https://github.com/metwork-framework/mfext/pull/360) ([thefab](https://github.com/thefab))
- build: Add '.init' utility in generated 'layer\_root'  documentation [\#358](https://github.com/metwork-framework/mfext/pull/358) ([dearith](https://github.com/dearith))
- build: fix tkinter import for python2 [\#355](https://github.com/metwork-framework/mfext/pull/355) ([thefab](https://github.com/thefab))
- build: add tcl/tk dependencies for scientific\_core [\#350](https://github.com/metwork-framework/mfext/pull/350) ([thefab](https://github.com/thefab))
- build: add tkinter test [\#347](https://github.com/metwork-framework/mfext/pull/347) ([thefab](https://github.com/thefab))
- build: add runtime dependencies for use of module tkinter in python2/3 [\#344](https://github.com/metwork-framework/mfext/pull/344) ([thebaptiste](https://github.com/thebaptiste))
- docs: fix invalid generated images link url [\#343](https://github.com/metwork-framework/mfext/pull/343) ([dearith](https://github.com/dearith))
- feat: add libev component [\#342](https://github.com/metwork-framework/mfext/pull/342) ([thefab](https://github.com/thefab))
- build: obsoletes recently deleted python3 layer [\#341](https://github.com/metwork-framework/mfext/pull/341) ([thefab](https://github.com/thefab))
- fix: obsoletes removed python layer [\#340](https://github.com/metwork-framework/mfext/pull/340) ([thefab](https://github.com/thefab))
- build: remove python layer [\#338](https://github.com/metwork-framework/mfext/pull/338) ([thebaptiste](https://github.com/thebaptiste))
-  docs: Update MFEXT documentation [\#337](https://github.com/metwork-framework/mfext/pull/337) ([dearith](https://github.com/dearith))
- fix: add a patch for openresty about nginx upstreams [\#333](https://github.com/metwork-framework/mfext/pull/333) ([thefab](https://github.com/thefab))
- build: add terminaltables also for python2 [\#332](https://github.com/metwork-framework/mfext/pull/332) ([thefab](https://github.com/thefab))
- fix: use python3 to build glib2 python tools and remove references to… [\#331](https://github.com/metwork-framework/mfext/pull/331) ([thebaptiste](https://github.com/thebaptiste))
- feat: restore env after exiting plugin\_env [\#329](https://github.com/metwork-framework/mfext/pull/329) ([thefab](https://github.com/thefab))
- feat: add terminaltables component [\#328](https://github.com/metwork-framework/mfext/pull/328) ([thefab](https://github.com/thefab))
- build: fix the display of usage message as root \(for CI\) [\#327](https://github.com/metwork-framework/mfext/pull/327) ([thefab](https://github.com/thefab))
- chore: move sysctl\_metwork.conf to mfcom [\#326](https://github.com/metwork-framework/mfext/pull/326) ([thefab](https://github.com/thefab))
- chore: don't use plugin name for building plugin home [\#325](https://github.com/metwork-framework/mfext/pull/325) ([thefab](https://github.com/thefab))
- feat: add some sysctl tunings [\#324](https://github.com/metwork-framework/mfext/pull/324) ([thefab](https://github.com/thefab))
- feat: add werkzeug component \(python wsgi toolbox\) [\#323](https://github.com/metwork-framework/mfext/pull/323) ([thefab](https://github.com/thefab))
- feat: keep request\_id field in logs [\#322](https://github.com/metwork-framework/mfext/pull/322) ([thefab](https://github.com/thefab))
- feat: add sqlite3 and libspatialite supports to gdal [\#321](https://github.com/metwork-framework/mfext/pull/321) ([thebaptiste](https://github.com/thebaptiste))
- fix: update internal circus version to fix a bug with async\_kill feature [\#319](https://github.com/metwork-framework/mfext/pull/319) ([thefab](https://github.com/thefab))
- feat: openresty update \(1.11.2.2 =\> 1.13.6.2\) [\#318](https://github.com/metwork-framework/mfext/pull/318) ([thefab](https://github.com/thefab))
- feat: update openjdk 11.0.1 =\> 11.0.2 and add mirror [\#316](https://github.com/metwork-framework/mfext/pull/316) ([thefab](https://github.com/thefab))
- docs: Update MFEXT documentation [\#314](https://github.com/metwork-framework/mfext/pull/314) ([dearith](https://github.com/dearith))
- build: update cookiecutter\_hooks [\#313](https://github.com/metwork-framework/mfext/pull/313) ([thefab](https://github.com/thefab))
- feat: add cookiecutter\_hooks project [\#312](https://github.com/metwork-framework/mfext/pull/312) ([thefab](https://github.com/thefab))
- docs: Update MFEXT documentation [\#311](https://github.com/metwork-framework/mfext/pull/311) ([dearith](https://github.com/dearith))
- feat: add search\_paths feature to cookiecutter [\#309](https://github.com/metwork-framework/mfext/pull/309) ([thefab](https://github.com/thefab))
- Proxy [\#308](https://github.com/metwork-framework/mfext/pull/308) ([thefab](https://github.com/thefab))
- feat: urllib3 update \(1.23 =\> 1.24.2\) because of upstream security issue [\#307](https://github.com/metwork-framework/mfext/pull/307) ([thefab](https://github.com/thefab))
- feat: allow to build mfext behing a corporate http proxy [\#306](https://github.com/metwork-framework/mfext/pull/306) ([thefab](https://github.com/thefab))
- fix: jinja2 update \(security\) 2.10 =\> 2.10.1 [\#303](https://github.com/metwork-framework/mfext/pull/303) ([thefab](https://github.com/thefab))
- feat: remove support gdk, gtk and qt from graphviz [\#300](https://github.com/metwork-framework/mfext/pull/300) ([lepetitnuage31](https://github.com/lepetitnuage31))
- feat: add graphviz in devtools layer \(for documentation\) [\#297](https://github.com/metwork-framework/mfext/pull/297) ([thefab](https://github.com/thefab))
- build: clean some old things [\#296](https://github.com/metwork-framework/mfext/pull/296) ([thefab](https://github.com/thefab))
- docs: Update MFEXT documentation [\#295](https://github.com/metwork-framework/mfext/pull/295) ([dearith](https://github.com/dearith))
- refactor: each single layer rpm of a branch now provides the same single [\#294](https://github.com/metwork-framework/mfext/pull/294) ([thebaptiste](https://github.com/thebaptiste))
- fix: don't launch mflog2mfadmin is admin hostname is null [\#292](https://github.com/metwork-framework/mfext/pull/292) ([thefab](https://github.com/thefab))
- build: mflog update \(fix latest commit\) [\#290](https://github.com/metwork-framework/mfext/pull/290) ([thefab](https://github.com/thefab))
- feat: update mflog [\#288](https://github.com/metwork-framework/mfext/pull/288) ([thefab](https://github.com/thefab))
- feat: remove prerequirements files [\#287](https://github.com/metwork-framework/mfext/pull/287) ([thebaptiste](https://github.com/thebaptiste))
- feat: update mflog and use new automatic context function [\#286](https://github.com/metwork-framework/mfext/pull/286) ([thefab](https://github.com/thefab))
- build: add a download mirror for sloccount [\#282](https://github.com/metwork-framework/mfext/pull/282) ([thefab](https://github.com/thefab))
- fix: more reliable checks about some circus watchers [\#280](https://github.com/metwork-framework/mfext/pull/280) ([thefab](https://github.com/thefab))
- fix: upgrade mflog to fix metwork-framework/mflog\#8 [\#279](https://github.com/metwork-framework/mfext/pull/279) ([thefab](https://github.com/thefab))
- fix: only the layers corresponding to the current addon should be in the [\#278](https://github.com/metwork-framework/mfext/pull/278) ([thebaptiste](https://github.com/thebaptiste))
- refactor: Use MFEXT\_ADDON\_NAME \(in root.mk\) to decide which layers sh… [\#277](https://github.com/metwork-framework/mfext/pull/277) ([thebaptiste](https://github.com/thebaptiste))
- feat: telegraf update [\#276](https://github.com/metwork-framework/mfext/pull/276) ([thefab](https://github.com/thefab))
- fix: fix the making of circus.ini from template on mfadmin \(mfadmin.s… [\#275](https://github.com/metwork-framework/mfext/pull/275) ([thebaptiste](https://github.com/thebaptiste))
- feat: mflog update [\#274](https://github.com/metwork-framework/mfext/pull/274) ([thefab](https://github.com/thefab))
- build: build fix \(numpy integration test must be deleted here\) [\#273](https://github.com/metwork-framework/mfext/pull/273) ([thefab](https://github.com/thefab))
- feat: introduce mflog2mfadmin feature [\#272](https://github.com/metwork-framework/mfext/pull/272) ([thefab](https://github.com/thefab))
- build: remove numpy from mfext \(will be transferred to [\#271](https://github.com/metwork-framework/mfext/pull/271) ([thebaptiste](https://github.com/thebaptiste))
- refactor: build python prerequirements in separate directory [\#270](https://github.com/metwork-framework/mfext/pull/270) ([thebaptiste](https://github.com/thebaptiste))
- build: typo [\#269](https://github.com/metwork-framework/mfext/pull/269) ([thefab](https://github.com/thefab))
- build: tmp obsoletes mfext metapackages [\#268](https://github.com/metwork-framework/mfext/pull/268) ([thefab](https://github.com/thefab))
- build: bump epoch [\#267](https://github.com/metwork-framework/mfext/pull/267) ([thefab](https://github.com/thefab))
- \[WIP\]feat: split old scientific layer between scientific\_core layer [\#264](https://github.com/metwork-framework/mfext/pull/264) ([thebaptiste](https://github.com/thebaptiste))
- feat: try to keep a backup of user files during uninstall [\#260](https://github.com/metwork-framework/mfext/pull/260) ([thefab](https://github.com/thefab))

## [v0.6.3](https://github.com/metwork-framework/mfext/tree/v0.6.3) (2019-05-25)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.10...v0.6.3)

**Implemented enhancements:**

- There should be no references to python27 scl in glib2 python tools and whe should use python3 to build these tools [\#330](https://github.com/metwork-framework/mfext/issues/330)

**Merged pull requests:**

- fix: close mflog issue11 [\#365](https://github.com/metwork-framework/mfext/pull/365) ([thefab](https://github.com/thefab))

## [v0.5.10](https://github.com/metwork-framework/mfext/tree/v0.5.10) (2019-05-21)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.6.2...v0.5.10)

**Merged pull requests:**

- build: fix tcl/tk requirements [\#359](https://github.com/metwork-framework/mfext/pull/359) ([thefab](https://github.com/thefab))
- Automatic backport of pull request \#355 [\#356](https://github.com/metwork-framework/mfext/pull/356) ([mergify[bot]](https://github.com/apps/mergify))
- build: add tcl/tk requirements [\#354](https://github.com/metwork-framework/mfext/pull/354) ([thefab](https://github.com/thefab))
- Automatic backport of pull request \#347 [\#348](https://github.com/metwork-framework/mfext/pull/348) ([mergify[bot]](https://github.com/apps/mergify))
- feat: add tkinter support thanks to a buildimage change [\#345](https://github.com/metwork-framework/mfext/pull/345) ([thefab](https://github.com/thefab))

## [v0.6.2](https://github.com/metwork-framework/mfext/tree/v0.6.2) (2019-05-20)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.6.1...v0.6.2)

**Implemented enhancements:**

- add sqlite and spatialite support to gdal [\#301](https://github.com/metwork-framework/mfext/issues/301)
- provide an automatic list of mfext components [\#25](https://github.com/metwork-framework/mfext/issues/25)

**Fixed bugs:**

- can't update integration RPMs since python layer drop [\#339](https://github.com/metwork-framework/mfext/issues/339)

**Merged pull requests:**

- Automatic backport of pull request \#355 [\#357](https://github.com/metwork-framework/mfext/pull/357) ([mergify[bot]](https://github.com/apps/mergify))
- build: add tcl/tk requirements [\#353](https://github.com/metwork-framework/mfext/pull/353) ([thefab](https://github.com/thefab))
- Automatic backport of pull request \#347 [\#349](https://github.com/metwork-framework/mfext/pull/349) ([mergify[bot]](https://github.com/apps/mergify))
- feat: add python tkinter support thanks to a change to the buildimage [\#346](https://github.com/metwork-framework/mfext/pull/346) ([thefab](https://github.com/thefab))

## [v0.6.1](https://github.com/metwork-framework/mfext/tree/v0.6.1) (2019-04-28)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.9...v0.6.1)

**Closed issues:**

- Compilation of 0500\_openjdk failed [\#315](https://github.com/metwork-framework/mfext/issues/315)

**Merged pull requests:**

- Automatic backport of pull request \#316 [\#317](https://github.com/metwork-framework/mfext/pull/317) ([mergify[bot]](https://github.com/apps/mergify))
- Automatic backport of pull request \#307 [\#310](https://github.com/metwork-framework/mfext/pull/310) ([mergify[bot]](https://github.com/apps/mergify))
- Automatic backport of pull request \#303 [\#305](https://github.com/metwork-framework/mfext/pull/305) ([mergify[bot]](https://github.com/apps/mergify))
- build: fix latest commit [\#291](https://github.com/metwork-framework/mfext/pull/291) ([thefab](https://github.com/thefab))
- fix: backport of \#279 to fix metwork-framework/mflog\#8 [\#289](https://github.com/metwork-framework/mfext/pull/289) ([thefab](https://github.com/thefab))

## [v0.5.9](https://github.com/metwork-framework/mfext/tree/v0.5.9) (2019-04-24)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.8...v0.5.9)

**Implemented enhancements:**

- be able to compile mfext behing a corporate http proxy [\#293](https://github.com/metwork-framework/mfext/issues/293)
- remove all prerequirements stuff in mfext [\#285](https://github.com/metwork-framework/mfext/issues/285)
- Define meta packages "scientific" and "python2" somewhere [\#283](https://github.com/metwork-framework/mfext/issues/283)
- move glib2/mfutil\_c/layerapi2/wrappers to core layer \(if possible\) [\#251](https://github.com/metwork-framework/mfext/issues/251)
- numpy should move to scientific layer [\#190](https://github.com/metwork-framework/mfext/issues/190)

**Fixed bugs:**

- pango problems with latest centos7 on release\_0.5 branch [\#261](https://github.com/metwork-framework/mfext/issues/261)

**Closed issues:**

- remove support gdk, gtk and qt from graphviz [\#299](https://github.com/metwork-framework/mfext/issues/299)

**Merged pull requests:**

- Automatic backport of pull request \#303 [\#304](https://github.com/metwork-framework/mfext/pull/304) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.5.8](https://github.com/metwork-framework/mfext/tree/v0.5.8) (2019-04-01)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.6.0...v0.5.8)

**Implemented enhancements:**

- modify sphinx conf.py to add automod api [\#236](https://github.com/metwork-framework/mfext/issues/236)

**Merged pull requests:**

- build: fix glib2 update [\#265](https://github.com/metwork-framework/mfext/pull/265) ([thefab](https://github.com/thefab))
- feat: upgrade glib2 from 2.40.2 to 2.56.4 [\#263](https://github.com/metwork-framework/mfext/pull/263) ([thefab](https://github.com/thefab))
- Automatic backport of pull request \#247 [\#254](https://github.com/metwork-framework/mfext/pull/254) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.6.0](https://github.com/metwork-framework/mfext/tree/v0.6.0) (2019-03-27)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.7...v0.6.0)

**Implemented enhancements:**

- mfext profile does not work well with ksh [\#243](https://github.com/metwork-framework/mfext/issues/243)
- mfext profile does not work well with zsh [\#62](https://github.com/metwork-framework/mfext/issues/62)

**Fixed bugs:**

- can't install "metwork-mfext-scientific" metapackage in some cases [\#255](https://github.com/metwork-framework/mfext/issues/255)

**Merged pull requests:**

- build: mflog update \(again\) [\#258](https://github.com/metwork-framework/mfext/pull/258) ([thefab](https://github.com/thefab))
- fix: fix some rpm upgrades [\#256](https://github.com/metwork-framework/mfext/pull/256) ([thefab](https://github.com/thefab))
- fix: upgrade problems at RPM levels [\#253](https://github.com/metwork-framework/mfext/pull/253) ([thefab](https://github.com/thefab))
- feat: refuse mfxxx.stop/start if the config.ini is newer than the cur… [\#252](https://github.com/metwork-framework/mfext/pull/252) ([thefab](https://github.com/thefab))
- Mflog update3 [\#249](https://github.com/metwork-framework/mfext/pull/249) ([thefab](https://github.com/thefab))
- Pci upgrade glib2 [\#248](https://github.com/metwork-framework/mfext/pull/248) ([thefab](https://github.com/thefab))
- feat: use our cookiecutter fork to add some features [\#247](https://github.com/metwork-framework/mfext/pull/247) ([thefab](https://github.com/thefab))
- Ci mfutil c [\#246](https://github.com/metwork-framework/mfext/pull/246) ([thefab](https://github.com/thefab))
- Buildfix3 [\#242](https://github.com/metwork-framework/mfext/pull/242) ([thefab](https://github.com/thefab))
- build: fix layer root branch when branch is not integration or master [\#241](https://github.com/metwork-framework/mfext/pull/241) ([thebaptiste](https://github.com/thebaptiste))
- fix: fix some installation issues in some corner cases [\#239](https://github.com/metwork-framework/mfext/pull/239) ([thefab](https://github.com/thefab))
- feat: add sphinx-automodapi module [\#238](https://github.com/metwork-framework/mfext/pull/238) ([thefab](https://github.com/thefab))
- feat: add a first version of jsonlog2elasticsearch [\#237](https://github.com/metwork-framework/mfext/pull/237) ([thefab](https://github.com/thefab))
- fix: fix mfxxx.start/stop/status when used in some special dirs [\#234](https://github.com/metwork-framework/mfext/pull/234) ([thefab](https://github.com/thefab))
- feat: delete filebeat component [\#233](https://github.com/metwork-framework/mfext/pull/233) ([thefab](https://github.com/thefab))
- build: rpm epoch bump [\#230](https://github.com/metwork-framework/mfext/pull/230) ([thefab](https://github.com/thefab))
- refactor: expose an unsafe\_pip command \(for manual use\) and use it [\#229](https://github.com/metwork-framework/mfext/pull/229) ([thefab](https://github.com/thefab))
- feat: remove python3\_ia layer \(we are building an dedicated addon for [\#227](https://github.com/metwork-framework/mfext/pull/227) ([thefab](https://github.com/thefab))
- feat: introduce mfext addons [\#225](https://github.com/metwork-framework/mfext/pull/225) ([thefab](https://github.com/thefab))
- feat: mflog update \(again\) [\#224](https://github.com/metwork-framework/mfext/pull/224) ([thefab](https://github.com/thefab))
- Mflog update [\#223](https://github.com/metwork-framework/mfext/pull/223) ([thefab](https://github.com/thefab))
- feat: upgrade mflog to latest master [\#222](https://github.com/metwork-framework/mfext/pull/222) ([thefab](https://github.com/thefab))
- Issue31 [\#220](https://github.com/metwork-framework/mfext/pull/220) ([thebaptiste](https://github.com/thebaptiste))
- fix: mapserverapi update \(0.1.2 =\> 0.1.3\) [\#218](https://github.com/metwork-framework/mfext/pull/218) ([thefab](https://github.com/thefab))
- fix: upgrade mapserverapi \(0.1.1 =\> 0.1.2\) [\#214](https://github.com/metwork-framework/mfext/pull/214) ([thefab](https://github.com/thefab))
- fix: rpm names with release tags [\#209](https://github.com/metwork-framework/mfext/pull/209) ([thefab](https://github.com/thefab))
- fix: force epoch=1 in centos7 openssl dependency [\#208](https://github.com/metwork-framework/mfext/pull/208) ([thebaptiste](https://github.com/thebaptiste))
- refactor: changes for the new mflog lib [\#207](https://github.com/metwork-framework/mfext/pull/207) ([thefab](https://github.com/thefab))
- feat: Upgrade postgis from 2.4.4 to 2.4.6 [\#206](https://github.com/metwork-framework/mfext/pull/206) ([thebaptiste](https://github.com/thebaptiste))
- feat: Upgrade geos from 3.6.2 to 3.7.1 \(with scl for C++11 on centos6\) [\#205](https://github.com/metwork-framework/mfext/pull/205) ([thebaptiste](https://github.com/thebaptiste))
- build: fix outside build [\#202](https://github.com/metwork-framework/mfext/pull/202) ([thefab](https://github.com/thefab))
- feat: add an utility "outside" to execute commands outside the metwork env [\#200](https://github.com/metwork-framework/mfext/pull/200) ([thefab](https://github.com/thefab))
- \[WIP\] feat: introduce new mflog library [\#198](https://github.com/metwork-framework/mfext/pull/198) ([thefab](https://github.com/thefab))
- \[WIP\] refactor: little change for conditional init in mfadmin [\#170](https://github.com/metwork-framework/mfext/pull/170) ([thefab](https://github.com/thefab))

## [v0.5.7](https://github.com/metwork-framework/mfext/tree/v0.5.7) (2019-03-16)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.6...v0.5.7)

## [v0.5.6](https://github.com/metwork-framework/mfext/tree/v0.5.6) (2019-03-15)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.5...v0.5.6)

**Implemented enhancements:**

- add sphinx-automodapi to the python3\_devtools layer [\#235](https://github.com/metwork-framework/mfext/issues/235)
- add a first version of jsonlog2elasticsearch to mfext [\#232](https://github.com/metwork-framework/mfext/issues/232)
- remove filebeat from mfext [\#231](https://github.com/metwork-framework/mfext/issues/231)

**Closed issues:**

- minimize mfext [\#228](https://github.com/metwork-framework/mfext/issues/228)

**Merged pull requests:**

- Automatic backport of pull request \#239 [\#240](https://github.com/metwork-framework/mfext/pull/240) ([mergify[bot]](https://github.com/apps/mergify))
- feat: introduce mfext addons [\#226](https://github.com/metwork-framework/mfext/pull/226) ([thefab](https://github.com/thefab))
- Automatic backport of pull request \#220 [\#221](https://github.com/metwork-framework/mfext/pull/221) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.5.5](https://github.com/metwork-framework/mfext/tree/v0.5.5) (2019-02-09)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.4...v0.5.5)

## [v0.5.4](https://github.com/metwork-framework/mfext/tree/v0.5.4) (2019-02-08)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.3...v0.5.4)

**Implemented enhancements:**

- merge "upgrade mapserverapi \(0.1.1 =\> 0.1.2\)" to 0.5 branch [\#215](https://github.com/metwork-framework/mfext/issues/215)

**Merged pull requests:**

- Automatic backport of pull request \#218 [\#219](https://github.com/metwork-framework/mfext/pull/219) ([mergify[bot]](https://github.com/apps/mergify))
- Mapserverapiupgrade05 [\#216](https://github.com/metwork-framework/mfext/pull/216) ([thefab](https://github.com/thefab))

## [v0.5.3](https://github.com/metwork-framework/mfext/tree/v0.5.3) (2019-02-05)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.2...v0.5.3)

**Implemented enhancements:**

- add an "outside" utility to execute a commande outside the metwork env [\#199](https://github.com/metwork-framework/mfext/issues/199)

**Closed issues:**

- Upgrade GEOS library to latest version \(3.7.1\) [\#204](https://github.com/metwork-framework/mfext/issues/204)

**Merged pull requests:**

- Automatic backport of pull request \#206 [\#213](https://github.com/metwork-framework/mfext/pull/213) ([mergify[bot]](https://github.com/apps/mergify))
- fix: obsoletes wrong named packages [\#212](https://github.com/metwork-framework/mfext/pull/212) ([thefab](https://github.com/thefab))
- Automatic backport of pull request \#208 [\#211](https://github.com/metwork-framework/mfext/pull/211) ([mergify[bot]](https://github.com/apps/mergify))
- Automatic backport of pull request \#209 [\#210](https://github.com/metwork-framework/mfext/pull/210) ([mergify[bot]](https://github.com/apps/mergify))
- Automatic backport of pull request \#202 [\#203](https://github.com/metwork-framework/mfext/pull/203) ([mergify[bot]](https://github.com/apps/mergify))
- Automatic backport of pull request \#200 [\#201](https://github.com/metwork-framework/mfext/pull/201) ([mergify[bot]](https://github.com/apps/mergify))

## [v0.5.2](https://github.com/metwork-framework/mfext/tree/v0.5.2) (2019-01-31)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.1...v0.5.2)

## [v0.5.1](https://github.com/metwork-framework/mfext/tree/v0.5.1) (2019-01-29)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.5.0...v0.5.1)

## [v0.5.0](https://github.com/metwork-framework/mfext/tree/v0.5.0) (2019-01-29)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.4.1...v0.5.0)

**Merged pull requests:**

- \[WIP\] feat: execute integration tests directly from mfext module [\#197](https://github.com/metwork-framework/mfext/pull/197) ([thebaptiste](https://github.com/thebaptiste))
- cleaner plugin file [\#196](https://github.com/metwork-framework/mfext/pull/196) ([frdcms](https://github.com/frdcms))
- feat: user-defined configuration name [\#195](https://github.com/metwork-framework/mfext/pull/195) ([frdcms](https://github.com/frdcms))
- \[wip\] add ia layer [\#194](https://github.com/metwork-framework/mfext/pull/194) ([thefab](https://github.com/thefab))
- feat: add some metapackages aliases to have a cleaner installation doc [\#193](https://github.com/metwork-framework/mfext/pull/193) ([thefab](https://github.com/thefab))
- feat: we remove the src directory from .plugin files [\#192](https://github.com/metwork-framework/mfext/pull/192) ([thefab](https://github.com/thefab))
- \[WIP\] feat: Simplify \_metwork.spec with self discovery of layer dependencies [\#189](https://github.com/metwork-framework/mfext/pull/189) ([thebaptiste](https://github.com/thebaptiste))
- circus update [\#187](https://github.com/metwork-framework/mfext/pull/187) ([thefab](https://github.com/thefab))
- fix: do not include .git\* files in the plugin RPM [\#186](https://github.com/metwork-framework/mfext/pull/186) ([frdcms](https://github.com/frdcms))
- feat: ignore lines starting with \# in .layerapi2\_dependencies/conflicts [\#185](https://github.com/metwork-framework/mfext/pull/185) ([thefab](https://github.com/thefab))
- Fix rpm naming2 [\#184](https://github.com/metwork-framework/mfext/pull/184) ([thefab](https://github.com/thefab))
- fix: rpm names was incorrect with release tags [\#181](https://github.com/metwork-framework/mfext/pull/181) ([thefab](https://github.com/thefab))
- build: add DRONE\_TAG support [\#180](https://github.com/metwork-framework/mfext/pull/180) ([thefab](https://github.com/thefab))
- \[WIP\] feat: lua-resty-stats upgrade \(0.0.2 =\> 0.0.3\) [\#179](https://github.com/metwork-framework/mfext/pull/179) ([thefab](https://github.com/thefab))
- build: remove a warning in docker environment during installation [\#178](https://github.com/metwork-framework/mfext/pull/178) ([thefab](https://github.com/thefab))
- build: add wget as dependency [\#177](https://github.com/metwork-framework/mfext/pull/177) ([thefab](https://github.com/thefab))
- \[wip\] feat: upgrade python3 from 3.5.3 to 3.5.6 and python2 from 2.7.9 to [\#176](https://github.com/metwork-framework/mfext/pull/176) ([thefab](https://github.com/thefab))
- build: \#174 fix [\#175](https://github.com/metwork-framework/mfext/pull/175) ([thefab](https://github.com/thefab))
- build: move circus\_autorestart\_plugin to mfext [\#174](https://github.com/metwork-framework/mfext/pull/174) ([thefab](https://github.com/thefab))
- build: change for new autorestart feature [\#173](https://github.com/metwork-framework/mfext/pull/173) ([thefab](https://github.com/thefab))
- \[WIP\] build: change numbering scheme for CI [\#169](https://github.com/metwork-framework/mfext/pull/169) ([thefab](https://github.com/thefab))
- build: fix template specfile when module has only root layer [\#167](https://github.com/metwork-framework/mfext/pull/167) ([thebaptiste](https://github.com/thebaptiste))
- build: fix specfile template to ignore dependency "python" [\#166](https://github.com/metwork-framework/mfext/pull/166) ([thebaptiste](https://github.com/thebaptiste))
- build: metwork specfile template evolution according to \#160 [\#165](https://github.com/metwork-framework/mfext/pull/165) ([thebaptiste](https://github.com/thebaptiste))
- feat: upgrade netCDF4 python from 1.4.0 to 1.4.2 [\#163](https://github.com/metwork-framework/mfext/pull/163) ([thebaptiste](https://github.com/thebaptiste))
- feat: telegraf update \(1.7.4 =\> 1.9.1\) [\#161](https://github.com/metwork-framework/mfext/pull/161) ([thefab](https://github.com/thefab))
- layer monitoring [\#159](https://github.com/metwork-framework/mfext/pull/159) ([thefab](https://github.com/thefab))
- feat: add openjdk as a non default layer [\#158](https://github.com/metwork-framework/mfext/pull/158) ([thefab](https://github.com/thefab))
- build: use liquidprompt official latest release [\#157](https://github.com/metwork-framework/mfext/pull/157) ([thebaptiste](https://github.com/thebaptiste))
- build: use sqlite.org official download link [\#156](https://github.com/metwork-framework/mfext/pull/156) ([thebaptiste](https://github.com/thebaptiste))
- feat: update urllib3 \(1.22 =\> 1.23\) [\#155](https://github.com/metwork-framework/mfext/pull/155) ([thefab](https://github.com/thefab))
- refactor: use the new plugin\_wrapper [\#151](https://github.com/metwork-framework/mfext/pull/151) ([thefab](https://github.com/thefab))
- \[WIP\] feat: clean some useless files in .plugin files \(part1\) [\#140](https://github.com/metwork-framework/mfext/pull/140) ([thefab](https://github.com/thefab))

## [v0.4.1](https://github.com/metwork-framework/mfext/tree/v0.4.1) (2019-01-10)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/v0.4.0...v0.4.1)

**Merged pull requests:**

- fix: rpm names were incorrect with release tags [\#183](https://github.com/metwork-framework/mfext/pull/183) ([thefab](https://github.com/thefab))

## [v0.4.0](https://github.com/metwork-framework/mfext/tree/v0.4.0) (2019-01-08)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/changelog_start...v0.4.0)

**Implemented enhancements:**

- problem with guess\_version.sh in drone environement in a release branch [\#168](https://github.com/metwork-framework/mfext/issues/168)
- Simplify \_metwork.spec with one rpm for each layer and self discovery of list of layers and dependencies [\#160](https://github.com/metwork-framework/mfext/issues/160)
- when a plugin is installed/used before "make release", we find some useless files in ".plugin" file [\#139](https://github.com/metwork-framework/mfext/issues/139)
- add python-diskcache module in python3 layer [\#136](https://github.com/metwork-framework/mfext/issues/136)
- add some python packages in python3\_scientific \(from pypi\) [\#127](https://github.com/metwork-framework/mfext/issues/127)
- in some cases, mfserv.stop/mfserv.start seems to do bad things in a plugin\_env [\#112](https://github.com/metwork-framework/mfext/issues/112)
- provide a way to use npm out of the box inside a "plugin env"  [\#95](https://github.com/metwork-framework/mfext/issues/95)
- provide a way to use pip out of the box inside a "plugin env" [\#91](https://github.com/metwork-framework/mfext/issues/91)
- liquidprompt-thefab20141015.tar.gz is a derived work [\#88](https://github.com/metwork-framework/mfext/issues/88)
- why we use sqlite-autoconf-3080803.tar.gz ? [\#87](https://github.com/metwork-framework/mfext/issues/87)
- add python3 support for eccodes [\#79](https://github.com/metwork-framework/mfext/issues/79)
- add an integration test about mapserverapi\_python integration [\#77](https://github.com/metwork-framework/mfext/issues/77)
- Add Postgresql Driver in GDAL \(OGR2OGR\) [\#76](https://github.com/metwork-framework/mfext/issues/76)
- add mapserver software [\#51](https://github.com/metwork-framework/mfext/issues/51)
- find a way to automatically document which RPM contains which layer [\#26](https://github.com/metwork-framework/mfext/issues/26)
- add a test framework for mfext [\#5](https://github.com/metwork-framework/mfext/issues/5)
- move boost away from core layer [\#3](https://github.com/metwork-framework/mfext/issues/3)
- chore: new conditional downstream [\#22](https://github.com/metwork-framework/mfext/pull/22) ([thefab](https://github.com/thefab))

**Fixed bugs:**

- no postgis in mfext rpms [\#109](https://github.com/metwork-framework/mfext/issues/109)
- no sqlite support for python3 \(not tested for python2\) [\#4](https://github.com/metwork-framework/mfext/issues/4)

**Closed issues:**

- Upgrade Netcdf4 python library to 1.4.2 [\#162](https://github.com/metwork-framework/mfext/issues/162)
- In mfxxx.status, add test to verify module crontab is not empty [\#122](https://github.com/metwork-framework/mfext/issues/122)
- in a docker container, we can't do "su - mfdata" for example [\#84](https://github.com/metwork-framework/mfext/issues/84)
- test issue [\#31](https://github.com/metwork-framework/mfext/issues/31)
- test issue [\#30](https://github.com/metwork-framework/mfext/issues/30)
- better buildcache [\#15](https://github.com/metwork-framework/mfext/issues/15)

**Merged pull requests:**

- Automatic backport of pull request \#169 [\#172](https://github.com/metwork-framework/mfext/pull/172) ([mergify[bot]](https://github.com/apps/mergify))
- build: fix build issue \(typo\) [\#154](https://github.com/metwork-framework/mfext/pull/154) ([thefab](https://github.com/thefab))
- Revert "feat: add lib, local/lib to `PYTHONPATH` by default \(layers, … [\#153](https://github.com/metwork-framework/mfext/pull/153) ([thefab](https://github.com/thefab))
- build: add a new watcher in circus template [\#152](https://github.com/metwork-framework/mfext/pull/152) ([thefab](https://github.com/thefab))
- feat: expose new function in layerapi2 [\#150](https://github.com/metwork-framework/mfext/pull/150) ([thefab](https://github.com/thefab))
- build: add basic integration test for Fiona [\#149](https://github.com/metwork-framework/mfext/pull/149) ([thebaptiste](https://github.com/thebaptiste))
- feat: add Fiona in python2/3 scientific layers [\#148](https://github.com/metwork-framework/mfext/pull/148) ([thebaptiste](https://github.com/thebaptiste))
- feat: add lib, local/lib to `PYTHONPATH` by default \(layers, plugins...\) [\#147](https://github.com/metwork-framework/mfext/pull/147) ([thefab](https://github.com/thefab))
- feat: upgrade eccodes from 2.9.0 to 2.10.0 and add python3 support in python3\_scientific [\#146](https://github.com/metwork-framework/mfext/pull/146) ([thebaptiste](https://github.com/thebaptiste))
- fix: fix layer dependencies in new tests [\#145](https://github.com/metwork-framework/mfext/pull/145) ([thebaptiste](https://github.com/thebaptiste))
- feat: telegraf update \(1.7.1 =\> 1.7.4\) [\#144](https://github.com/metwork-framework/mfext/pull/144) ([thefab](https://github.com/thefab))
- feat: add diskcache in python2 and python3 layers [\#143](https://github.com/metwork-framework/mfext/pull/143) ([thebaptiste](https://github.com/thebaptiste))
- feat: add graphviz and pygraphviz [\#142](https://github.com/metwork-framework/mfext/pull/142) ([thebaptiste](https://github.com/thebaptiste))
- feat: telegraf is now monitoring itself [\#141](https://github.com/metwork-framework/mfext/pull/141) ([thefab](https://github.com/thefab))
- fix: mapserverapi upgrade \(0.1.0 =\> 0.1.1\) [\#138](https://github.com/metwork-framework/mfext/pull/138) ([thefab](https://github.com/thefab))
- Issue 127 [\#137](https://github.com/metwork-framework/mfext/pull/137) ([thebaptiste](https://github.com/thebaptiste))
- build: build fix [\#134](https://github.com/metwork-framework/mfext/pull/134) ([thefab](https://github.com/thefab))
- Issue127 [\#132](https://github.com/metwork-framework/mfext/pull/132) ([thebaptiste](https://github.com/thebaptiste))
- Issue127 [\#131](https://github.com/metwork-framework/mfext/pull/131) ([thebaptiste](https://github.com/thebaptiste))
- feat: guess released versions with tags [\#130](https://github.com/metwork-framework/mfext/pull/130) ([thefab](https://github.com/thefab))
- feat: Add possibility to pip install package from https url. [\#129](https://github.com/metwork-framework/mfext/pull/129) ([thebaptiste](https://github.com/thebaptiste))
- feat: better default MODULE\_RUNTIME\_SUFFIX [\#128](https://github.com/metwork-framework/mfext/pull/128) ([thefab](https://github.com/thefab))
- Update .drone.yml [\#126](https://github.com/metwork-framework/mfext/pull/126) ([thefab](https://github.com/thefab))
- Update .drone.yml [\#125](https://github.com/metwork-framework/mfext/pull/125) ([thefab](https://github.com/thefab))
- build: prepare release\_\* branches [\#124](https://github.com/metwork-framework/mfext/pull/124) ([thefab](https://github.com/thefab))
- feat: check that module crontab is not empy in mfxxx.status [\#123](https://github.com/metwork-framework/mfext/pull/123) ([thebaptiste](https://github.com/thebaptiste))
- feat: add geos, lxml, pycurl, pyproj and sqlalchemy [\#121](https://github.com/metwork-framework/mfext/pull/121) ([thefab](https://github.com/thefab))
- build: migrate integration tests system [\#120](https://github.com/metwork-framework/mfext/pull/120) ([thebaptiste](https://github.com/thebaptiste))
- chore: sync common files from resources repository [\#117](https://github.com/metwork-framework/mfext/pull/117) ([metworkbot](https://github.com/metworkbot))
- Update README.md [\#116](https://github.com/metwork-framework/mfext/pull/116) ([thefab](https://github.com/thefab))
- chore: sync common files from resources repository [\#115](https://github.com/metwork-framework/mfext/pull/115) ([metworkbot](https://github.com/metworkbot))
- CHANGELOG automatic update [\#114](https://github.com/metwork-framework/mfext/pull/114) ([metworkbot](https://github.com/metworkbot))
- fix: block mfxxx.start/stop/status/init calls from a plugin\_env [\#113](https://github.com/metwork-framework/mfext/pull/113) ([thefab](https://github.com/thefab))
- chore: sync common files from resources repository [\#111](https://github.com/metwork-framework/mfext/pull/111) ([metworkbot](https://github.com/metworkbot))
-  build: Move postgresql in scientific layer. [\#110](https://github.com/metwork-framework/mfext/pull/110) ([thebaptiste](https://github.com/thebaptiste))
- build: fix runtime dependencies for centos6 [\#108](https://github.com/metwork-framework/mfext/pull/108) ([thefab](https://github.com/thefab))
- add lscpu dependency [\#107](https://github.com/metwork-framework/mfext/pull/107) ([thefab](https://github.com/thefab))
- build: trigger testimage builds [\#106](https://github.com/metwork-framework/mfext/pull/106) ([thefab](https://github.com/thefab))
- build: add which as a core dependency [\#105](https://github.com/metwork-framework/mfext/pull/105) ([thefab](https://github.com/thefab))
- build: fix packaging issue introduced by latest changes [\#104](https://github.com/metwork-framework/mfext/pull/104) ([thefab](https://github.com/thefab))
- build: better build cache hash \(again\) [\#103](https://github.com/metwork-framework/mfext/pull/103) ([thefab](https://github.com/thefab))
- build: fix typo for mfserv build [\#102](https://github.com/metwork-framework/mfext/pull/102) ([thefab](https://github.com/thefab))
- build: faster rpm packaging [\#101](https://github.com/metwork-framework/mfext/pull/101) ([thefab](https://github.com/thefab))
- share cache between integration, master, ci\_\* and pci\_\* branches [\#100](https://github.com/metwork-framework/mfext/pull/100) ([thefab](https://github.com/thefab))
- Sharecachrevert [\#99](https://github.com/metwork-framework/mfext/pull/99) ([thefab](https://github.com/thefab))
- build: shared cache fix [\#98](https://github.com/metwork-framework/mfext/pull/98) ([thefab](https://github.com/thefab))
- CHANGELOG automatic update [\#97](https://github.com/metwork-framework/mfext/pull/97) ([metworkbot](https://github.com/metworkbot))
- \[DO NOT MERGE\] feat: use normal "npm" workflow inside a "plugin\_env" [\#96](https://github.com/metwork-framework/mfext/pull/96) ([thefab](https://github.com/thefab))
- fix: add mapserverapi\_python [\#94](https://github.com/metwork-framework/mfext/pull/94) ([thebaptiste](https://github.com/thebaptiste))
- CHANGELOG automatic update [\#93](https://github.com/metwork-framework/mfext/pull/93) ([metworkbot](https://github.com/metworkbot))
- feat: now we can use pip inside a "plugin env" [\#92](https://github.com/metwork-framework/mfext/pull/92) ([thefab](https://github.com/thefab))
- feat: patch certifi for using system certificates on centos [\#90](https://github.com/metwork-framework/mfext/pull/90) ([thefab](https://github.com/thefab))
- chore: sync common files from resources repository [\#89](https://github.com/metwork-framework/mfext/pull/89) ([metworkbot](https://github.com/metworkbot))
- fix: mfxxx login problems in docker mode [\#85](https://github.com/metwork-framework/mfext/pull/85) ([thefab](https://github.com/thefab))
- CHANGELOG automatic update [\#83](https://github.com/metwork-framework/mfext/pull/83) ([metworkbot](https://github.com/metworkbot))
- \[DO NOT MERGE\] share caches between integration, master, ci\_\* and pci\_\* branches [\#82](https://github.com/metwork-framework/mfext/pull/82) ([thefab](https://github.com/thefab))
- Move cairo from layer3\_mapserver to layer1\_scientific [\#81](https://github.com/metwork-framework/mfext/pull/81) ([thebaptiste](https://github.com/thebaptiste))
- Support postgresql in gdal [\#80](https://github.com/metwork-framework/mfext/pull/80) ([thebaptiste](https://github.com/thebaptiste))
- chore: sync common files from resources repository [\#78](https://github.com/metwork-framework/mfext/pull/78) ([metworkbot](https://github.com/metworkbot))
- CHANGELOG automatic update [\#75](https://github.com/metwork-framework/mfext/pull/75) ([metworkbot](https://github.com/metworkbot))
- CHANGELOG automatic update [\#74](https://github.com/metwork-framework/mfext/pull/74) ([metworkbot](https://github.com/metworkbot))
- feat: add mapserverapi\_python [\#73](https://github.com/metwork-framework/mfext/pull/73) ([thefab](https://github.com/thefab))
- chore: sync common files from resources repository [\#72](https://github.com/metwork-framework/mfext/pull/72) ([metworkbot](https://github.com/metworkbot))
- build: ignore .metwork-framework directory from cache hash [\#71](https://github.com/metwork-framework/mfext/pull/71) ([thefab](https://github.com/thefab))
- feat: add mapserverapi library [\#70](https://github.com/metwork-framework/mfext/pull/70) ([thefab](https://github.com/thefab))
- feat: load mapserver layer by default \(if available\) [\#69](https://github.com/metwork-framework/mfext/pull/69) ([thefab](https://github.com/thefab))
- feat: we can now use plugin\_env function in a plugin directory [\#68](https://github.com/metwork-framework/mfext/pull/68) ([thefab](https://github.com/thefab))
- doc: add some documentation [\#67](https://github.com/metwork-framework/mfext/pull/67) ([thefab](https://github.com/thefab))
- CHANGELOG automatic update [\#65](https://github.com/metwork-framework/mfext/pull/65) ([metworkbot](https://github.com/metworkbot))
- feat: upgrade eccodes to 2.9.0 [\#64](https://github.com/metwork-framework/mfext/pull/64) ([thefab](https://github.com/thefab))
- build: fix a spec issue with new system limits [\#61](https://github.com/metwork-framework/mfext/pull/61) ([thefab](https://github.com/thefab))
- build: add a FORCED\_OS\_VERSION parameter [\#59](https://github.com/metwork-framework/mfext/pull/59) ([thefab](https://github.com/thefab))
- feat: upgrade python requests because of security alert [\#58](https://github.com/metwork-framework/mfext/pull/58) ([thefab](https://github.com/thefab))
- build: add some additional sources for vim as we have problem with main [\#57](https://github.com/metwork-framework/mfext/pull/57) ([thefab](https://github.com/thefab))
- fix: depency issue with new mapserver subpackage [\#56](https://github.com/metwork-framework/mfext/pull/56) ([thefab](https://github.com/thefab))
- CHANGELOG automatic update [\#55](https://github.com/metwork-framework/mfext/pull/55) ([metworkbot](https://github.com/metworkbot))
- feat: mapserver introduction [\#54](https://github.com/metwork-framework/mfext/pull/54) ([thefab](https://github.com/thefab))
- chore: sync common files from resources repository [\#53](https://github.com/metwork-framework/mfext/pull/53) ([metworkbot](https://github.com/metworkbot))
- feat: we increase some system limits \(nofile and nproc\) [\#52](https://github.com/metwork-framework/mfext/pull/52) ([thefab](https://github.com/thefab))
- feat: add pytest package and update some other ones [\#50](https://github.com/metwork-framework/mfext/pull/50) ([thefab](https://github.com/thefab))
- build: potentially faster build for ci\_\* branches [\#48](https://github.com/metwork-framework/mfext/pull/48) ([thefab](https://github.com/thefab))
- CHANGELOG automatic update [\#46](https://github.com/metwork-framework/mfext/pull/46) ([metworkbot](https://github.com/metworkbot))
- chore: add trigger\_tests to run integration tests [\#45](https://github.com/metwork-framework/mfext/pull/45) ([thebaptiste](https://github.com/thebaptiste))
- feat: add integration\_tests layer and rpm mfext-integration-tests [\#44](https://github.com/metwork-framework/mfext/pull/44) ([thebaptiste](https://github.com/thebaptiste))
- temp revert of \#38 [\#43](https://github.com/metwork-framework/mfext/pull/43) ([thefab](https://github.com/thefab))
- chore: sync common files from resources repository [\#39](https://github.com/metwork-framework/mfext/pull/39) ([metworkbot](https://github.com/metworkbot))
- chore: add trigger\_tests to run integration tests [\#38](https://github.com/metwork-framework/mfext/pull/38) ([thebaptiste](https://github.com/thebaptiste))
- chore: sync common files from resources repository [\#37](https://github.com/metwork-framework/mfext/pull/37) ([metworkbot](https://github.com/metworkbot))
- chore: sync common files from resources repository [\#36](https://github.com/metwork-framework/mfext/pull/36) ([metworkbot](https://github.com/metworkbot))
- build: ignore all .md and .yml files for computing build hash [\#35](https://github.com/metwork-framework/mfext/pull/35) ([thefab](https://github.com/thefab))
- chore: sync common files from resources repository [\#34](https://github.com/metwork-framework/mfext/pull/34) ([metworkbot](https://github.com/metworkbot))
- build: re-add /buildcache as volume for build step [\#28](https://github.com/metwork-framework/mfext/pull/28) ([thefab](https://github.com/thefab))
- chore: management of branches ci\_\* and pci\_\* [\#27](https://github.com/metwork-framework/mfext/pull/27) ([thebaptiste](https://github.com/thebaptiste))
- chore: package createrepo is now in build image [\#24](https://github.com/metwork-framework/mfext/pull/24) ([thebaptiste](https://github.com/thebaptiste))
- chore: move boost from core layer to scientific layer [\#23](https://github.com/metwork-framework/mfext/pull/23) ([thebaptiste](https://github.com/thebaptiste))
- chore: readd /buildcache volume in build step [\#21](https://github.com/metwork-framework/mfext/pull/21) ([thefab](https://github.com/thefab))
- chore: better build cache [\#20](https://github.com/metwork-framework/mfext/pull/20) ([thebaptiste](https://github.com/thebaptiste))
- add mergify support [\#17](https://github.com/metwork-framework/mfext/pull/17) ([thefab](https://github.com/thefab))
- chore: fix new build\_cache hash [\#14](https://github.com/metwork-framework/mfext/pull/14) ([thefab](https://github.com/thefab))
- chore: add a new build\_cache hash [\#13](https://github.com/metwork-framework/mfext/pull/13) ([thefab](https://github.com/thefab))
- chore: fix build issue \(when the build of the core layer is cached\) [\#11](https://github.com/metwork-framework/mfext/pull/11) ([thefab](https://github.com/thefab))
- feat: add websocket support for openresty [\#10](https://github.com/metwork-framework/mfext/pull/10) ([thefab](https://github.com/thefab))
- docs: add badges to README [\#9](https://github.com/metwork-framework/mfext/pull/9) ([thefab](https://github.com/thefab))
- chore: build cache for glib2 [\#8](https://github.com/metwork-framework/mfext/pull/8) ([thefab](https://github.com/thefab))
- chore: fix build cache for core layer [\#7](https://github.com/metwork-framework/mfext/pull/7) ([thefab](https://github.com/thefab))
- fix: sqlite support for python2/python3 [\#6](https://github.com/metwork-framework/mfext/pull/6) ([thefab](https://github.com/thefab))

## [changelog_start](https://github.com/metwork-framework/mfext/tree/changelog_start) (2018-09-19)

[Full Changelog](https://github.com/metwork-framework/mfext/compare/00adaf7adf459ac881153b76fb615e458f96a5aa...changelog_start)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
