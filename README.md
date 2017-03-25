# api documentation for  [pm2 (v2.4.2)](http://pm2.keymetrics.io/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pm2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pm2)
#### Production process manager for Node.JS applications with a built-in load balancer.

[![NPM](https://nodei.co/npm/pm2.png?downloads=true)](https://www.npmjs.com/package/pm2)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-pm2_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-pm2/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Strzelewicz Alexandre",
        "email": "alexandre@keymetrics.io",
        "url": "https://keymetrics.io"
    },
    "bin": {
        "pm2": "./bin/pm2",
        "rundev": "./bin/rundev",
        "pm2-dev": "./bin/pm2-dev",
        "pm2-docker": "./bin/pm2-docker"
    },
    "bugs": {
        "url": "https://github.com/Unitech/pm2/issues"
    },
    "contributors": [
        {
            "name": "Alex Kocharin",
            "email": "alex@kocharin.ru"
        },
        {
            "name": "Soyuka",
            "email": "soyuka@gmail.com"
        },
        {
            "name": "Joni Shkurti",
            "email": "jonishkurti90@gmail.com"
        },
        {
            "name": "James Ide"
        },
        {
            "name": "Jun Tjatse",
            "email": "thisnamemeansnothing@gmail.com"
        },
        {
            "name": "Xu Jingxin",
            "email": "sailxjx@gmail.com"
        },
        {
            "name": "Ben Postlethwaite",
            "email": "post.ben.here@gmail.com"
        },
        {
            "name": "Devo.ps",
            "email": "contact@devo.ps"
        },
        {
            "name": "Bret Copeland",
            "email": "bret@atlantisflight.org"
        },
        {
            "name": "John Hurliman",
            "email": "jhurliman@jhurliman.org"
        },
        {
            "name": "TruongSinh Tran-Nguyen",
            "email": "i@truongsinh.pro"
        },
        {
            "name": "Michael Hueuberger",
            "email": "michael.heuberger@binarykitchen.com"
        },
        {
            "email": "chris@chriswiggins.co.nz"
        }
    ],
    "dependencies": {
        "async": "1.5",
        "blessed": "^0.1.81",
        "chalk": "^1.1",
        "chokidar": "^1.6.1",
        "cli-table": "0.3.1",
        "commander": "^2.9",
        "cron": "1.2.1",
        "debug": "^2.3.2",
        "eventemitter2": "1.0.5",
        "fclone": "1.0.11",
        "gkt": "https://tgz.pm2.io/gkt-1.0.0.tgz",
        "mkdirp": "0.5.1",
        "moment": "^2.15",
        "nssocket": "0.6.0",
        "pidusage": "^1.1.0",
        "pm2-axon": "3.0.2",
        "pm2-axon-rpc": "0.4.5",
        "pm2-deploy": "^0.3.5",
        "pm2-multimeter": "^0.1.2",
        "pmx": "^1.0.2",
        "semver": "^5.2",
        "shelljs": "0.7.6",
        "source-map-support": "^0.4.6",
        "sprintf-js": "~1.0.2",
        "vizion": "^0.2",
        "yamljs": "0.2.8"
    },
    "description": "Production process manager for Node.JS applications with a built-in load balancer.",
    "devDependencies": {
        "mocha": "^3",
        "should": "^11"
    },
    "directories": {
        "bin": "./bin",
        "lib": "./lib",
        "example": "./examples"
    },
    "dist": {
        "shasum": "7afa1176773c3bebac962ad52e8261a270175027",
        "tarball": "https://registry.npmjs.org/pm2/-/pm2-2.4.2.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "64df5fb31afb1231fa78c03e824a6c9b7d4055b5",
    "homepage": "http://pm2.keymetrics.io/",
    "keywords": [
        "cli",
        "fault tolerant",
        "sysadmin",
        "tools",
        "pm2",
        "logs",
        "log",
        "json",
        "express",
        "hapi",
        "kraken",
        "reload",
        "microservice",
        "programmatic",
        "harmony",
        "node-pm2",
        "production",
        "keymetrics",
        "node.js monitoring",
        "strong-pm",
        "deploy",
        "deployment",
        "daemon",
        "supervisor",
        "nodemon",
        "pm2.io",
        "ghost",
        "ghost production",
        "monitoring",
        "process manager",
        "forever",
        "profiling",
        "probes",
        "forever-monitor",
        "keep process alive",
        "process configuration",
        "clustering",
        "cluster cli",
        "cluster",
        "cron",
        "devops",
        "dev ops"
    ],
    "license": "AGPL-3.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "tknew",
            "email": "strzelewicz.alexandre@gmail.com"
        }
    ],
    "name": "pm2",
    "optionalDependencies": {
        "gkt": "https://tgz.pm2.io/gkt-1.0.0.tgz"
    },
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Unitech/pm2.git"
    },
    "scripts": {
        "test": "NODE_ENV=test bash test/pm2_programmatic_tests.sh && NODE_ENV=test bash test/pm2_behavior_tests.sh"
    },
    "version": "2.4.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module pm2](#apidoc.module.pm2)
1.  boolean <span class="apidocSignatureSpan">pm2.</span>daemon_mode
1.  boolean <span class="apidocSignatureSpan">pm2.</span>gl_is_km_linked
1.  [function <span class="apidocSignatureSpan">pm2.</span>Daemon (opts)](#apidoc.element.pm2.Daemon)
1.  [function <span class="apidocSignatureSpan">pm2.</span>custom (opts)](#apidoc.element.pm2.custom)
1.  object <span class="apidocSignatureSpan">pm2.</span>Client
1.  object <span class="apidocSignatureSpan">pm2.</span>Client.prototype
1.  object <span class="apidocSignatureSpan">pm2.</span>Common
1.  object <span class="apidocSignatureSpan">pm2.</span>Configuration
1.  object <span class="apidocSignatureSpan">pm2.</span>Daemon.prototype
1.  object <span class="apidocSignatureSpan">pm2.</span>God
1.  object <span class="apidocSignatureSpan">pm2.</span>Satan
1.  object <span class="apidocSignatureSpan">pm2.</span>Utility
1.  object <span class="apidocSignatureSpan">pm2.</span>_conf
1.  object <span class="apidocSignatureSpan">pm2.</span>completion
1.  object <span class="apidocSignatureSpan">pm2.</span>custom.prototype
1.  object <span class="apidocSignatureSpan">pm2.</span>gl_interact_infos
1.  object <span class="apidocSignatureSpan">pm2.</span>machine_name
1.  object <span class="apidocSignatureSpan">pm2.</span>public_key
1.  object <span class="apidocSignatureSpan">pm2.</span>secret_key
1.  object <span class="apidocSignatureSpan">pm2.</span>start_timer
1.  string <span class="apidocSignatureSpan">pm2.</span>cwd
1.  string <span class="apidocSignatureSpan">pm2.</span>pm2_home

#### [module pm2.Client](#apidoc.module.pm2.Client)
1.  [function <span class="apidocSignatureSpan">pm2.</span>Client (opts)](#apidoc.element.pm2.Client.Client)

#### [module pm2.Client.prototype](#apidoc.module.pm2.Client.prototype)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>close (cb)](#apidoc.element.pm2.Client.prototype.close)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>disconnectBus (cb)](#apidoc.element.pm2.Client.prototype.disconnectBus)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>disconnectRPC (cb)](#apidoc.element.pm2.Client.prototype.disconnectRPC)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>executeRemote (method, app_conf, fn)](#apidoc.element.pm2.Client.prototype.executeRemote)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getAllModulesId (cb)](#apidoc.element.pm2.Client.prototype.getAllModulesId)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getAllProcess (cb)](#apidoc.element.pm2.Client.prototype.getAllProcess)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getAllProcessId (cb)](#apidoc.element.pm2.Client.prototype.getAllProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getExposedMethods (cb)](#apidoc.element.pm2.Client.prototype.getExposedMethods)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getProcessByName (name, cb)](#apidoc.element.pm2.Client.prototype.getProcessByName)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getProcessIdByName (name, force_all, cb)](#apidoc.element.pm2.Client.prototype.getProcessIdByName)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>initFileStructure (opts)](#apidoc.element.pm2.Client.prototype.initFileStructure)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>killDaemon (fn)](#apidoc.element.pm2.Client.prototype.killDaemon)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>launchBus (cb)](#apidoc.element.pm2.Client.prototype.launchBus)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>launchDaemon (opts, cb)](#apidoc.element.pm2.Client.prototype.launchDaemon)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>launchRPC (cb)](#apidoc.element.pm2.Client.prototype.launchRPC)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>notifyGod (action_name, id, cb)](#apidoc.element.pm2.Client.prototype.notifyGod)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>pingDaemon (cb)](#apidoc.element.pm2.Client.prototype.pingDaemon)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>start (cb)](#apidoc.element.pm2.Client.prototype.start)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>startWatch (method, env, fn)](#apidoc.element.pm2.Client.prototype.startWatch)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>stopWatch (method, env, fn)](#apidoc.element.pm2.Client.prototype.stopWatch)
1.  [function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>toggleWatch (method, env, fn)](#apidoc.element.pm2.Client.prototype.toggleWatch)

#### [module pm2.Common](#apidoc.module.pm2.Common)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>clone (obj)](#apidoc.element.pm2.Common.clone)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>deepCopy (obj)](#apidoc.element.pm2.Common.deepCopy)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>extend (destination, source)](#apidoc.element.pm2.Common.extend)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>isConfigFile (filename)](#apidoc.element.pm2.Common.isConfigFile)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>mergeEnvironmentVariables (app_env, env_name, deploy_conf)](#apidoc.element.pm2.Common.mergeEnvironmentVariables)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>parseConfig (confObj, filename)](#apidoc.element.pm2.Common.parseConfig)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>prepareAppConf (opts, app)](#apidoc.element.pm2.Common.prepareAppConf)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>printError (msg)](#apidoc.element.pm2.Common.printError)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>printOut ()](#apidoc.element.pm2.Common.printOut)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>resolveAppAttributes (opts, legacy_app)](#apidoc.element.pm2.Common.resolveAppAttributes)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>retErr (e)](#apidoc.element.pm2.Common.retErr)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>safeExtend (origin, add)](#apidoc.element.pm2.Common.safeExtend)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>serialize (obj)](#apidoc.element.pm2.Common.serialize)
1.  [function <span class="apidocSignatureSpan">pm2.Common.</span>verifyConfs (appConfs)](#apidoc.element.pm2.Common.verifyConfs)
1.  object <span class="apidocSignatureSpan">pm2.Common.</span>sink

#### [module pm2.Configuration](#apidoc.module.pm2.Configuration)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>get (key, cb)](#apidoc.element.pm2.Configuration.get)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>getAll (cb)](#apidoc.element.pm2.Configuration.getAll)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>getAllSync ()](#apidoc.element.pm2.Configuration.getAllSync)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>getSync (key)](#apidoc.element.pm2.Configuration.getSync)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>multiset (serial, cb)](#apidoc.element.pm2.Configuration.multiset)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>set (key, value, cb)](#apidoc.element.pm2.Configuration.set)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>setSync (key, value)](#apidoc.element.pm2.Configuration.setSync)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>unset (key, cb)](#apidoc.element.pm2.Configuration.unset)
1.  [function <span class="apidocSignatureSpan">pm2.Configuration.</span>unsetSync (key)](#apidoc.element.pm2.Configuration.unsetSync)

#### [module pm2.Daemon](#apidoc.module.pm2.Daemon)
1.  [function <span class="apidocSignatureSpan">pm2.</span>Daemon (opts)](#apidoc.element.pm2.Daemon.Daemon)

#### [module pm2.Daemon.prototype](#apidoc.module.pm2.Daemon.prototype)
1.  [function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>close (opts, cb)](#apidoc.element.pm2.Daemon.prototype.close)
1.  [function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>gracefullExit ()](#apidoc.element.pm2.Daemon.prototype.gracefullExit)
1.  [function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>handleSignals ()](#apidoc.element.pm2.Daemon.prototype.handleSignals)
1.  [function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>innerStart (cb)](#apidoc.element.pm2.Daemon.prototype.innerStart)
1.  [function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>sendReady (cb)](#apidoc.element.pm2.Daemon.prototype.sendReady)
1.  [function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>start ()](#apidoc.element.pm2.Daemon.prototype.start)
1.  [function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>startLogic ()](#apidoc.element.pm2.Daemon.prototype.startLogic)

#### [module pm2.God](#apidoc.module.pm2.God)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>checkProcess (pid)](#apidoc.element.pm2.God.checkProcess)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>deleteProcessId (id, cb)](#apidoc.element.pm2.God.deleteProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>dumpProcessList (cb)](#apidoc.element.pm2.God.dumpProcessList)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>duplicateProcessId (id, cb)](#apidoc.element.pm2.God.duplicateProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>executeApp (env, cb)](#apidoc.element.pm2.God.executeApp)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>finalizeProcedure (proc)](#apidoc.element.pm2.God.finalizeProcedure)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>findByName (name)](#apidoc.element.pm2.God.findByName)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>findProcessById (id)](#apidoc.element.pm2.God.findProcessById)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>forceGc (opts, cb)](#apidoc.element.pm2.God.forceGc)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>forkMode (pm2_env, cb)](#apidoc.element.pm2.God.forkMode)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>getFormatedProcess (id)](#apidoc.element.pm2.God.getFormatedProcess)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>getFormatedProcesses ()](#apidoc.element.pm2.God.getFormatedProcesses)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>getMonitorData (env, cb)](#apidoc.element.pm2.God.getMonitorData)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>getNewId ()](#apidoc.element.pm2.God.getNewId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>getProcesses ()](#apidoc.element.pm2.God.getProcesses)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>getSystemData (env, cb)](#apidoc.element.pm2.God.getSystemData)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>getVersion (env, cb)](#apidoc.element.pm2.God.getVersion)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>handleExit (clu, exit_code, kill_signal)](#apidoc.element.pm2.God.handleExit)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>killProcess (pid, pm2_env, cb)](#apidoc.element.pm2.God.killProcess)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>logAndGenerateError (err)](#apidoc.element.pm2.God.logAndGenerateError)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>msgProcess (cmd, cb)](#apidoc.element.pm2.God.msgProcess)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>nodeApp (env_copy, cb)](#apidoc.element.pm2.God.nodeApp)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>notify (action_name, data, manually)](#apidoc.element.pm2.God.notify)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>notifyByProcessId (opts, cb)](#apidoc.element.pm2.God.notifyByProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>notifyKillPM2 ()](#apidoc.element.pm2.God.notifyKillPM2)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>ping (env, cb)](#apidoc.element.pm2.God.ping)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>prepare (env, cb)](#apidoc.element.pm2.God.prepare)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>processIsDead (pid, pm2_env, cb, sigkill)](#apidoc.element.pm2.God.processIsDead)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>reloadLogs (opts, cb)](#apidoc.element.pm2.God.reloadLogs)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>reloadProcessId (opts, cb)](#apidoc.element.pm2.God.reloadProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>resetMetaProcessId (id, cb)](#apidoc.element.pm2.God.resetMetaProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>resetState (pm2_env)](#apidoc.element.pm2.God.resetState)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>restartProcessId (opts, cb)](#apidoc.element.pm2.God.restartProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>restartProcessName (name, cb)](#apidoc.element.pm2.God.restartProcessName)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>sendDataToProcessId (packet, cb)](#apidoc.element.pm2.God.sendDataToProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>sendSignalToProcessId (opts, cb)](#apidoc.element.pm2.God.sendSignalToProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>sendSignalToProcessName (opts, cb)](#apidoc.element.pm2.God.sendSignalToProcessName)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>softReloadProcessId (opts, cb)](#apidoc.element.pm2.God.softReloadProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>startProcessId (id, cb)](#apidoc.element.pm2.God.startProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>startWatch (method, value, fn)](#apidoc.element.pm2.God.startWatch)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>stopProcessId (id, cb)](#apidoc.element.pm2.God.stopProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>stopWatch (method, value, fn)](#apidoc.element.pm2.God.stopWatch)
1.  [function <span class="apidocSignatureSpan">pm2.God.</span>toggleWatch (method, value, fn)](#apidoc.element.pm2.God.toggleWatch)
1.  number <span class="apidocSignatureSpan">pm2.God.</span>next_id
1.  object <span class="apidocSignatureSpan">pm2.God.</span>Worker
1.  object <span class="apidocSignatureSpan">pm2.God.</span>bus
1.  object <span class="apidocSignatureSpan">pm2.God.</span>clusters_db
1.  object <span class="apidocSignatureSpan">pm2.God.</span>watch

#### [module pm2.Satan](#apidoc.module.pm2.Satan)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>disconnectBus (cb)](#apidoc.element.pm2.Satan.disconnectBus)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>disconnectRPC (cb)](#apidoc.element.pm2.Satan.disconnectRPC)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>executeRemote (method, env, fn)](#apidoc.element.pm2.Satan.executeRemote)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>getExposedMethods (cb)](#apidoc.element.pm2.Satan.getExposedMethods)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>killDaemon (fn)](#apidoc.element.pm2.Satan.killDaemon)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>launchBus (cb)](#apidoc.element.pm2.Satan.launchBus)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>launchDaemon (cb)](#apidoc.element.pm2.Satan.launchDaemon)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>launchRPC (cb)](#apidoc.element.pm2.Satan.launchRPC)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>notifyGod (action_name, id, cb)](#apidoc.element.pm2.Satan.notifyGod)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>pingDaemon (cb)](#apidoc.element.pm2.Satan.pingDaemon)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>printOut ()](#apidoc.element.pm2.Satan.printOut)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>processStateHandler (God)](#apidoc.element.pm2.Satan.processStateHandler)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>remoteWrapper ()](#apidoc.element.pm2.Satan.remoteWrapper)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>restartWatch (method, env, fn)](#apidoc.element.pm2.Satan.restartWatch)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>start (noDaemonMode, cb)](#apidoc.element.pm2.Satan.start)
1.  [function <span class="apidocSignatureSpan">pm2.Satan.</span>stopWatch (method, env, fn)](#apidoc.element.pm2.Satan.stopWatch)

#### [module pm2.Utility](#apidoc.module.pm2.Utility)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>clone (obj)](#apidoc.element.pm2.Utility.clone)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>extend (destination, source)](#apidoc.element.pm2.Utility.extend)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>extendExtraConfig (proc, opts)](#apidoc.element.pm2.Utility.extendExtraConfig)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>formatCLU (process)](#apidoc.element.pm2.Utility.formatCLU)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>getDate ()](#apidoc.element.pm2.Utility.getDate)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>overrideConsole (bus)](#apidoc.element.pm2.Utility.overrideConsole)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>packageNameToModuleName (package_name)](#apidoc.element.pm2.Utility.packageNameToModuleName)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>startLogging (stds, callback)](#apidoc.element.pm2.Utility.startLogging)
1.  [function <span class="apidocSignatureSpan">pm2.Utility.</span>whichFileExists (file_arr)](#apidoc.element.pm2.Utility.whichFileExists)

#### [module pm2.completion](#apidoc.module.pm2.completion)
1.  [function <span class="apidocSignatureSpan">pm2.completion.</span>complete (name, completer, cb)](#apidoc.element.pm2.completion.complete)
1.  [function <span class="apidocSignatureSpan">pm2.completion.</span>isComplete ()](#apidoc.element.pm2.completion.isComplete)
1.  [function <span class="apidocSignatureSpan">pm2.completion.</span>log (arr, o, prefix)](#apidoc.element.pm2.completion.log)
1.  [function <span class="apidocSignatureSpan">pm2.completion.</span>parseOut (str)](#apidoc.element.pm2.completion.parseOut)
1.  [function <span class="apidocSignatureSpan">pm2.completion.</span>parseTasks (str, prefix, reg)](#apidoc.element.pm2.completion.parseTasks)

#### [module pm2.custom](#apidoc.module.pm2.custom)
1.  [function <span class="apidocSignatureSpan">pm2.</span>custom (opts)](#apidoc.element.pm2.custom.custom)

#### [module pm2.custom.prototype](#apidoc.module.pm2.custom.prototype)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_handleAttributeUpdate (opts)](#apidoc.element.pm2.custom.prototype._handleAttributeUpdate)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_operate (action_name, process_name, envs, cb)](#apidoc.element.pm2.custom.prototype._operate)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_pre_interact (cmd, public_key, machine, info_node)](#apidoc.element.pm2.custom.prototype._pre_interact)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_pull (opts, cb)](#apidoc.element.pm2.custom.prototype._pull)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_pullCommitId (opts, cb)](#apidoc.element.pm2.custom.prototype._pullCommitId)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_startJson (file, opts, action, pipe, cb)](#apidoc.element.pm2.custom.prototype._startJson)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_startScript (script, opts, cb)](#apidoc.element.pm2.custom.prototype._startScript)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>actionFromJson (action, file, opts, jsonVia, cb)](#apidoc.element.pm2.custom.prototype.actionFromJson)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>backward (process_name, cb)](#apidoc.element.pm2.custom.prototype.backward)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>close (cb)](#apidoc.element.pm2.custom.prototype.close)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>conf (key, value, cb)](#apidoc.element.pm2.custom.prototype.conf)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>connect (noDaemon, cb)](#apidoc.element.pm2.custom.prototype.connect)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>dashboard (cb)](#apidoc.element.pm2.custom.prototype.dashboard)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>deepUpdate (cb)](#apidoc.element.pm2.custom.prototype.deepUpdate)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>delete (process_name, jsonVia, cb)](#apidoc.element.pm2.custom.prototype.delete)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>deleteModule (module_name, cb)](#apidoc.element.pm2.custom.prototype.deleteModule)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>deploy (file, commands, cb)](#apidoc.element.pm2.custom.prototype.deploy)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>describe (pm2_id, cb)](#apidoc.element.pm2.custom.prototype.describe)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>destroy (cb)](#apidoc.element.pm2.custom.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>disconnect (cb)](#apidoc.element.pm2.custom.prototype.disconnect)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>dockerMode (script, opts, mode)](#apidoc.element.pm2.custom.prototype.dockerMode)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>dump (cb)](#apidoc.element.pm2.custom.prototype.dump)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>exitCli (code)](#apidoc.element.pm2.custom.prototype.exitCli)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>flush (cb)](#apidoc.element.pm2.custom.prototype.flush)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>forward (process_name, cb)](#apidoc.element.pm2.custom.prototype.forward)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>generateDockerfile (script, opts)](#apidoc.element.pm2.custom.prototype.generateDockerfile)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>generateModuleSample (app_name, cb)](#apidoc.element.pm2.custom.prototype.generateModuleSample)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>generateSample (mode)](#apidoc.element.pm2.custom.prototype.generateSample)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>get (key, cb)](#apidoc.element.pm2.custom.prototype.get)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>getProcessIdByName (name, cb)](#apidoc.element.pm2.custom.prototype.getProcessIdByName)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>getVersion (cb)](#apidoc.element.pm2.custom.prototype.getVersion)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>gracefulReload (process_name, opts, cb)](#apidoc.element.pm2.custom.prototype.gracefulReload)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>install (module_name, cb)](#apidoc.element.pm2.custom.prototype.install)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>interact (secret_key, public_key, machine_name, cb)](#apidoc.element.pm2.custom.prototype.interact)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>interactInfos (cb)](#apidoc.element.pm2.custom.prototype.interactInfos)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>jlist (debug)](#apidoc.element.pm2.custom.prototype.jlist)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>kill (cb)](#apidoc.element.pm2.custom.prototype.kill)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>killAllModules (cb)](#apidoc.element.pm2.custom.prototype.killAllModules)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>killDaemon (cb)](#apidoc.element.pm2.custom.prototype.killDaemon)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>killInteract (cb)](#apidoc.element.pm2.custom.prototype.killInteract)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>launchBus (cb)](#apidoc.element.pm2.custom.prototype.launchBus)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>launchModules (cb)](#apidoc.element.pm2.custom.prototype.launchModules)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>list (opts, cb)](#apidoc.element.pm2.custom.prototype.list)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>logrotate (opts, cb)](#apidoc.element.pm2.custom.prototype.logrotate)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>monit (cb)](#apidoc.element.pm2.custom.prototype.monit)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>msgProcess (opts, cb)](#apidoc.element.pm2.custom.prototype.msgProcess)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>multiset (serial, cb)](#apidoc.element.pm2.custom.prototype.multiset)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>ping (cb)](#apidoc.element.pm2.custom.prototype.ping)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>printLogs (id, lines, raw, timestamp, exclusive)](#apidoc.element.pm2.custom.prototype.printLogs)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>profilePM2 (command, cb)](#apidoc.element.pm2.custom.prototype.profilePM2)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>publish (module_name, cb)](#apidoc.element.pm2.custom.prototype.publish)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullAndGracefulReload (process_name, cb)](#apidoc.element.pm2.custom.prototype.pullAndGracefulReload)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullAndReload (process_name, cb)](#apidoc.element.pm2.custom.prototype.pullAndReload)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullAndRestart (process_name, cb)](#apidoc.element.pm2.custom.prototype.pullAndRestart)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullCommitId (process_name, commit_id, cb)](#apidoc.element.pm2.custom.prototype.pullCommitId)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>reload (process_name, opts, cb)](#apidoc.element.pm2.custom.prototype.reload)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>reloadLogs (cb)](#apidoc.element.pm2.custom.prototype.reloadLogs)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>remote (command, opts, cb)](#apidoc.element.pm2.custom.prototype.remote)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>remoteV2 (command, opts, cb)](#apidoc.element.pm2.custom.prototype.remoteV2)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>reset (process_name, cb)](#apidoc.element.pm2.custom.prototype.reset)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>restart (cmd, opts, cb)](#apidoc.element.pm2.custom.prototype.restart)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>resurrect (cb)](#apidoc.element.pm2.custom.prototype.resurrect)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>scale (app_name, number, cb)](#apidoc.element.pm2.custom.prototype.scale)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>sendDataToProcessId (proc_id, packet, cb)](#apidoc.element.pm2.custom.prototype.sendDataToProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>sendSignalToProcessId (signal, process_id, cb)](#apidoc.element.pm2.custom.prototype.sendSignalToProcessId)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>sendSignalToProcessName (signal, process_name, cb)](#apidoc.element.pm2.custom.prototype.sendSignalToProcessName)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>serve (target_path, port, opts, cb)](#apidoc.element.pm2.custom.prototype.serve)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>set (key, value, cb)](#apidoc.element.pm2.custom.prototype.set)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>snapshotPM2 (cb)](#apidoc.element.pm2.custom.prototype.snapshotPM2)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>speedList (code)](#apidoc.element.pm2.custom.prototype.speedList)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>start (cmd, opts, cb)](#apidoc.element.pm2.custom.prototype.start)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>startup (platform, opts, cb)](#apidoc.element.pm2.custom.prototype.startup)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>stop (process_name, cb)](#apidoc.element.pm2.custom.prototype.stop)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>streamLogs (id, lines, raw, timestamp, exclusive)](#apidoc.element.pm2.custom.prototype.streamLogs)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>trigger (pm_id, action_name, params, cb)](#apidoc.element.pm2.custom.prototype.trigger)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>uninstall (module_name, cb)](#apidoc.element.pm2.custom.prototype.uninstall)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>uninstallStartup (platform, opts, cb)](#apidoc.element.pm2.custom.prototype.uninstallStartup)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>unset (key, cb)](#apidoc.element.pm2.custom.prototype.unset)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>update (cb)](#apidoc.element.pm2.custom.prototype.update)
1.  [function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>web (port, cb)](#apidoc.element.pm2.custom.prototype.web)



# <a name="apidoc.module.pm2"></a>[module pm2](#apidoc.module.pm2)

#### <a name="apidoc.element.pm2.Daemon"></a>[function <span class="apidocSignatureSpan">pm2.</span>Daemon (opts)](#apidoc.element.pm2.Daemon)
- description and source-code
```javascript
Daemon = function (opts) {
  if (!opts) opts = {};

  this.rpc_socket_ready = false;
  this.pub_socket_ready = false;

  this.pub_socket_file = opts.pub_socket_file || cst.DAEMON_PUB_PORT;
  this.rpc_socket_file = opts.rpc_socket_file || cst.DAEMON_RPC_PORT;

  this.pid_path        = opts.pid_file || cst.PM2_PID_FILE_PATH;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom"></a>[function <span class="apidocSignatureSpan">pm2.</span>custom (opts)](#apidoc.element.pm2.custom)
- description and source-code
```javascript
custom = function (opts) {
  if (!opts) opts = {};
  var that = this;

  this.daemon_mode = typeof(opts.daemon_mode) == 'undefined' ? true : opts.daemon_mode;
  this.pm2_home    = conf.PM2_ROOT_PATH;
  this.public_key   = process.env.KEYMETRICS_SECRET || opts.public_key || null;
  this.secret_key   = process.env.KEYMETRICS_PUBLIC || opts.secret_key || null;
  this.machine_name = process.env.INSTANCE_NAME || opts.machine_name || null

<span class="apidocCodeCommentSpan">  /**
   * CWD resolution
   */
</span>  this.cwd         = process.cwd();
  if (opts.cwd) {
    this.cwd = path.resolve(opts.cwd);
  }

  /**
   * PM2 HOME resolution
   */
  if (opts.pm2_home && opts.independent == true)
    throw new Error('You cannot set a pm2_home and independent instance in same time');

  if (opts.pm2_home) {
    // Override default conf file
    this.pm2_home        = opts.pm2_home;
    conf = util._extend(conf, path_structure(this.pm2_home));
  }
  else if (opts.independent == true && conf.IS_WINDOWS === false) {
    // Create an unique pm2 instance
    var crypto = require('crypto');
    var random_file = crypto.randomBytes(8).toString('hex');
    this.pm2_home = path.join('/tmp', random_file);

    // If we dont explicitly tell to have a daemon
    // It will go as in proc
    if (typeof(opts.daemon_mode) == 'undefined')
      this.daemon_mode = false;
    conf = util._extend(conf, path_structure(this.pm2_home));
  }

  this._conf = conf;

  if (conf.IS_WINDOWS) {
    // Weird fix, may need to be dropped
    // @todo windows connoisseur double check
    if (process.stdout._handle && process.stdout._handle.setBlocking)
      process.stdout._handle.setBlocking(true);
  }

  this.Client = new Client({
    pm2_home : that.pm2_home,
    conf     : this._conf,
    secret_key : this.secret_key,
    public_key : this.public_key,
    daemon_mode : this.daemon_mode,
    machine_name : this.machine_name
  });

  this.gl_interact_infos = null;
  this.gl_is_km_linked = false;

  try {
    var pid = fs.readFileSync(conf.INTERACTOR_PID_PATH);
    pid = parseInt(pid.toString().trim());
    process.kill(pid, 0);
    that.gl_is_km_linked = true;
  } catch(e) {
    that.gl_is_km_linked = false;
  }

  // For testing purposes
  if (this.secret_key && process.env.NODE_ENV == 'local_test')
    that.gl_is_km_linked = true;

  KMDaemon.getInteractInfo(this._conf, function(i_err, interact) {
    that.gl_interact_infos = interact;
  });
}
```
- example usage
```shell
...
var fmt       = require('./tools/fmt.js');
var exec      = require('child_process').exec;
var os        = require('os');

commander.version(pkg.version)
  .usage('[cmd] app');

var pm2 = new PM2.custom({
  pm2_home : path.join(os.homedir ? os.homedir() : (process.env.HOME || process.env.HOMEPATH || process.env.USERPROFILE), '.pm2-
dev')
});

pm2.connect(function() {
  commander.parse(process.argv);
});
...
```



# <a name="apidoc.module.pm2.Client"></a>[module pm2.Client](#apidoc.module.pm2.Client)

#### <a name="apidoc.element.pm2.Client.Client"></a>[function <span class="apidocSignatureSpan">pm2.</span>Client (opts)](#apidoc.element.pm2.Client.Client)
- description and source-code
```javascript
Client = function (opts) {
  if (!opts) opts = {};

  if (!opts.conf)
    this.conf = require('../constants.js');
  else {
    this.conf     = opts.conf;
  }

  this.daemon_mode = typeof(opts.daemon_mode) == 'undefined' ? true : opts.daemon_mode;
  this.pm2_home    = this.conf.PM2_ROOT_PATH;
  this.secret_key   = opts.secret_key;
  this.public_key   = opts.public_key;
  this.machine_name = opts.machine_name;

  // Create all folders and files needed
  // Client depends to that to interact with PM2 properly
  this.initFileStructure(this.conf);

  debug('Using RPC file %s', this.conf.DAEMON_RPC_PORT);
  debug('Using PUB file %s', this.conf.DAEMON_PUB_PORT);
  this.rpc_socket_file = this.conf.DAEMON_RPC_PORT;
  this.pub_socket_file = this.conf.DAEMON_PUB_PORT;
}
```
- example usage
```shell
...
 * @api public
 * @method pingDaemon
 * @param {} cb
 * @return
 */
Client.prototype.pingDaemon = function pingDaemon(cb) {
var req    = axon.socket('req');
var client = new rpc.Client(req);

debug('[PING PM2] Trying to connect to server');

client.sock.once('reconnect attempt', function() {
  client.sock.close();
  debug('Daemon not launched');
  process.nextTick(function() {
...
```



# <a name="apidoc.module.pm2.Client.prototype"></a>[module pm2.Client.prototype](#apidoc.module.pm2.Client.prototype)

#### <a name="apidoc.element.pm2.Client.prototype.close"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>close (cb)](#apidoc.element.pm2.Client.prototype.close)
- description and source-code
```javascript
close = function (cb) {
  var that = this;

  async.forEach([
    that.disconnectRPC.bind(that),
    that.disconnectBus.bind(that)
  ], function(fn, next) {
    fn(next)
  }, cb);
}
```
- example usage
```shell
...
Client.prototype.pingDaemon = function pingDaemon(cb) {
var req    = axon.socket('req');
var client = new rpc.Client(req);

debug('[PING PM2] Trying to connect to server');

client.sock.once('reconnect attempt', function() {
  client.sock.close();
  debug('Daemon not launched');
  process.nextTick(function() {
    return cb(false);
  });
});

client.sock.once('connect', function() {
...
```

#### <a name="apidoc.element.pm2.Client.prototype.disconnectBus"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>disconnectBus (cb)](#apidoc.element.pm2.Client.prototype.disconnectBus)
- description and source-code
```javascript
function disconnectBus(cb) {
  if (!cb) cb = noop;

  var that = this;

  if (!this.sub_sock || !this.sub_sock.close) {
    that.sub = null;
    return process.nextTick(function() {
      cb(null, { msg : 'bus was not connected'});
    });
  }

  if (this.sub_sock.connected == false ||
      this.sub_sock.closing == true) {
    that.sub = null;
    return process.nextTick(function() {
      cb(new Error('SUB connection is already being closed'));
    });
  }

  try {
    var timer;

    that.sub_sock.once('close', function() {
      that.sub = null;
      clearTimeout(timer);
      debug('PM2 PUB cleanly closed');
      return cb();
    });

    timer = setTimeout(function() {
      if (Client.sub_sock.destroy)
        that.sub_sock.destroy();
      return cb();
    }, 200);

    this.sub_sock.close();
  } catch(e) {
    return cb(e);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.disconnectRPC"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>disconnectRPC (cb)](#apidoc.element.pm2.Client.prototype.disconnectRPC)
- description and source-code
```javascript
function disconnectRPC(cb) {
  var that = this;
  if (!cb) cb = noop;

  if (!this.client_sock || !this.client_sock.close) {
    this.client = null;
    return process.nextTick(function() {
      cb(new Error('SUB connection to PM2 is not launched'));
    });
  }

  if (this.client_sock.connected == false ||
      this.client_sock.closing == true) {
    this.client = null;
    return process.nextTick(function() {
      cb(new Error('RPC already being closed'));
    });
  }

  try {
    var timer;

    that.client_sock.once('close', function() {
      clearTimeout(timer);
      that.client = null;
      debug('PM2 RPC cleanly closed');
      return cb(null, { msg : 'RPC Successfully closed' });
    });

    timer = setTimeout(function() {
      if (Client.client_sock.destroy)
        that.client_sock.destroy();
      that.client = null;
      return cb(null, { msg : 'RPC Successfully closed via timeout' });
    }, 200);

    that.client_sock.close();
  } catch(e) {
    debug('Error while disconnecting RPC PM2', e.stack || e);
    return cb(e);
  };
  return false;
}
```
- example usage
```shell
...
 * @param {} fn
 * @return
 */
Satan.killDaemon = function killDaemon(fn) {
var timeout;

function quit() {
  Satan.disconnectRPC(function() {
    debug('RPC disconnected');
    return fn ? fn(null, {success:true}) : false;
  });
}

process.once('SIGQUIT', function() {
  debug('Received SIGQUIT');
...
```

#### <a name="apidoc.element.pm2.Client.prototype.executeRemote"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>executeRemote (method, app_conf, fn)](#apidoc.element.pm2.Client.prototype.executeRemote)
- description and source-code
```javascript
function executeRemote(method, app_conf, fn) {
  var self = this;

  // stop watch on stop | env is the process id
  if (method.indexOf('stop') !== -1) {
    this.stopWatch(method, app_conf);
  }
  // stop watching when process is deleted
  else if (method.indexOf('delete') !== -1) {
    this.stopWatch(method, app_conf);
  }
  // stop everything on kill
  else if (method.indexOf('kill') !== -1) {
    this.stopWatch('deleteAll', app_conf);
  }
  else if (method.indexOf('restartProcessId') !== -1 && process.argv.indexOf('--watch') > -1) {
    delete app_conf.env.current_conf.watch;
    this.toggleWatch(method, app_conf);
  }

  if (!this.client || !this.client.call) {
    this.start(function(error) {
      if (error) {
        if (fn)
          return fn(error);
        console.error(error);
        return process.exit(0);
      }
      return self.client.call(method, app_conf, fn);
    });
    return false;
  }

  debug('Calling daemon method pm2:%s on rpc socket:%s', method, this.rpc_socket_file);
  return this.client.call(method, app_conf, fn);
}
```
- example usage
```shell
...
}

debug('Calling daemon method pm2:%s on rpc socket:%s', method, this.rpc_socket_file);
return this.client.call(method, app_conf, fn);
};

Client.prototype.notifyGod = function(action_name, id, cb) {
this.executeRemote('notifyByProcessId', {
  id : id,
  action_name : action_name,
  manually : true
}, function() {
  debug('God notified');
  return cb ? cb() : false;
});
...
```

#### <a name="apidoc.element.pm2.Client.prototype.getAllModulesId"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getAllModulesId (cb)](#apidoc.element.pm2.Client.prototype.getAllModulesId)
- description and source-code
```javascript
getAllModulesId = function (cb) {
  var found_proc = [];

  this.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      return cb(err);
    }

    list.forEach(function(proc) {
      if (proc.pm2_env.pmx_module)
        found_proc.push(proc.pm_id);
    });

    return cb(null, found_proc);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.getAllProcess"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getAllProcess (cb)](#apidoc.element.pm2.Client.prototype.getAllProcess)
- description and source-code
```javascript
getAllProcess = function (cb) {
  var found_proc = [];

  this.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      return cb(err);
    }

    list.forEach(function(proc) {
      found_proc.push(proc);
    });

    return cb(null, found_proc);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.getAllProcessId"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getAllProcessId (cb)](#apidoc.element.pm2.Client.prototype.getAllProcessId)
- description and source-code
```javascript
getAllProcessId = function (cb) {
  var found_proc = [];

  this.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      return cb(err);
    }

    list.forEach(function(proc) {
      if (!proc.pm2_env.pmx_module)
        found_proc.push(proc.pm_id);
    });

    return cb(null, found_proc);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.getExposedMethods"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getExposedMethods (cb)](#apidoc.element.pm2.Client.prototype.getExposedMethods)
- description and source-code
```javascript
function getExposedMethods(cb) {
  this.client.methods(cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.getProcessByName"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getProcessByName (name, cb)](#apidoc.element.pm2.Client.prototype.getProcessByName)
- description and source-code
```javascript
getProcessByName = function (name, cb) {
  var found_proc = [];

  this.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      return cb(err);
    }

    list.forEach(function(proc) {
      if (proc.pm2_env.name == name ||
          proc.pm2_env.pm_exec_path == path.resolve(name)) {
        found_proc.push(proc);
      }
    });

    return cb(null, found_proc);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.getProcessIdByName"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>getProcessIdByName (name, force_all, cb)](#apidoc.element.pm2.Client.prototype.getProcessIdByName)
- description and source-code
```javascript
getProcessIdByName = function (name, force_all, cb) {
  var found_proc   = [];
  var full_details = {};

  if (typeof(cb) === 'undefined') {
    cb = force_all;
    force_all = false;
  }

  if (typeof(name) == 'number')
    name = name.toString();

  this.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      return cb(err);
    }

    list.forEach(function(proc) {
      if ((proc.pm2_env.name == name || proc.pm2_env.pm_exec_path == path.resolve(name)) &&
          !(proc.pm2_env.pmx_module && !force_all)) {
        found_proc.push(proc.pm_id);
        full_details[proc.pm_id] = proc;
      }
    });

    return cb(null, found_proc, full_details);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.initFileStructure"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>initFileStructure (opts)](#apidoc.element.pm2.Client.prototype.initFileStructure)
- description and source-code
```javascript
initFileStructure = function (opts) {

  if (!fs.existsSync(opts.DEFAULT_LOG_PATH)) {
    try {
      mkdirp.sync(opts.DEFAULT_LOG_PATH);
    } catch (e) {
      console.error(e.stack || e);
    }
  }

  if (!fs.existsSync(opts.DEFAULT_PID_PATH)) {
    try {
      mkdirp.sync(opts.DEFAULT_PID_PATH);
    } catch (e) {
      console.error(e.stack || e);
    }
  }

  // No more (temporary) conf file, mainly via api now
  // @todo: implement configuration file for override
  // (before conf was only about path overrides)
  // if (!fs.existsSync(opts.PM2_CONF_FILE)) {
  //   fs
  //     .createReadStream(path.join(opts.TEMPLATE_FOLDER, opts.SAMPLE_CONF_FILE))
  //     .pipe(fs.createWriteStream(opts.PM2_CONF_FILE));
  // }

  if (!fs.existsSync(opts.PM2_MODULE_CONF_FILE)) {
    try {
      fs.writeFileSync(opts.PM2_MODULE_CONF_FILE, "{}");
    } catch (e) {
      console.error(e.stack || e);
    }
  }

  if (!process.env.PM2_PROGRAMMATIC && !fs.existsSync(path.join(opts.PM2_HOME, 'touch'))) {
    var dt = fs.readFileSync(path.join(__dirname, opts.KEYMETRICS_BANNER));
    console.log(dt.toString());
    try {
      fs.writeFileSync(path.join(opts.PM2_HOME, 'touch'), Date.now());
    } catch(e) {
      debug(e.stack || e);
    }
  }
}
```
- example usage
```shell
...
  this.pm2_home    = this.conf.PM2_ROOT_PATH;
  this.secret_key   = opts.secret_key;
  this.public_key   = opts.public_key;
  this.machine_name = opts.machine_name;

  // Create all folders and files needed
  // Client depends to that to interact with PM2 properly
  this.initFileStructure(this.conf);

  debug('Using RPC file %s', this.conf.DAEMON_RPC_PORT);
  debug('Using PUB file %s', this.conf.DAEMON_PUB_PORT);
  this.rpc_socket_file = this.conf.DAEMON_RPC_PORT;
  this.pub_socket_file = this.conf.DAEMON_PUB_PORT;
}
...
```

#### <a name="apidoc.element.pm2.Client.prototype.killDaemon"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>killDaemon (fn)](#apidoc.element.pm2.Client.prototype.killDaemon)
- description and source-code
```javascript
function killDaemon(fn) {
  var timeout;
  var that = this;

  function quit() {
    that.close(function() {
      return fn ? fn(null, {success:true}) : false;
    });
  }

  // under unix, we listen for signal (that is send by daemon to notify us that its shuting down)
  if (process.platform !== 'win32' && process.platform !== 'win64') {
    process.once('SIGQUIT', function() {
      debug('Received SIGQUIT from pm2 daemon');
      clearTimeout(timeout);
      quit();
    });
  }
  else {
    // if under windows, try to ping the daemon to see if it still here
    setTimeout(function() {
      that.pingDaemon(function(alive) {
        if (!alive) {
          clearTimeout(timeout);
          return quit();
        }
      });
    }, 250)
  }

  timeout = setTimeout(function() {
    quit();
  }, 3000);

  // Kill daemon
  this.executeRemote('killMe', {pid : process.pid});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.launchBus"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>launchBus (cb)](#apidoc.element.pm2.Client.prototype.launchBus)
- description and source-code
```javascript
function launchEventSystem(cb) {
  var self = this;
  this.sub = axon.socket('sub-emitter');
  this.sub_sock = this.sub.connect(this.pub_socket_file);

  this.sub_sock.once('connect', function() {
    return cb(null, self.sub, self.sub_sock);
  });
}
```
- example usage
```shell
...
fmt.field('Watch and Restart', chalk.green('Enabled'));
fmt.field('Ignored folder', opts.ignore_watch || 'node_modules');
if (opts.postExec)
  fmt.field('Post restart cmd', opts.postExec);
fmt.sep();

setTimeout(function() {
  pm2.Client.launchBus(function(err, bus) {
    bus.on('process:event', function(packet) {
      if (packet.event == 'online') {
        if (opts.postExec)
          postExecCmd(opts.postExec);
      }
    });
  });
...
```

#### <a name="apidoc.element.pm2.Client.prototype.launchDaemon"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>launchDaemon (opts, cb)](#apidoc.element.pm2.Client.prototype.launchDaemon)
- description and source-code
```javascript
launchDaemon = function (opts, cb) {
  if (typeof(opts) == 'function') {
    cb = opts;
    opts = {
      interactor : true
    };
  }

  var that = this
  var ClientJS = path.resolve(path.dirname(module.filename), 'Daemon.js');
  var node_args = [];
  var out, err;

  if (process.env.TRAVIS) {
    // Redirect PM2 internal err and out to STDERR STDOUT when running with Travis
    out = 1;
    err = 2;
  }
  else {
    out = fs.openSync(that.conf.PM2_LOG_FILE_PATH, 'a'),
    err = fs.openSync(that.conf.PM2_LOG_FILE_PATH, 'a');
  }

  // Node.js tuning for better performance
  //node_args.push('--expose-gc'); // Allows manual GC in the code
  //node_args.push('--gc-global'); // Does full GC (smaller memory footprint)
  //node_args.push('--max-old-space-size=100');

<span class="apidocCodeCommentSpan">  /**
   * Add node [arguments] depending on PM2_NODE_OPTIONS env variable
   */
</span>  if (process.env.PM2_NODE_OPTIONS)
    node_args = node_args.concat(process.env.PM2_NODE_OPTIONS.split(' '));
  node_args.push(ClientJS);

  Common.printOut(that.conf.PREFIX_MSG + 'Spawning PM2 daemon with pm2_home=' + this.pm2_home);

  var child = require('child_process').spawn(process.execPath || 'node', node_args, {
    detached   : true,
    cwd        : that.conf.cwd || process.cwd(),
    env        : util._extend({
      'SILENT'      : that.conf.DEBUG ? !that.conf.DEBUG : true,
      'PM2_HOME'   : that.pm2_home
    }, process.env),
    stdio      : ['ipc', out, err]
  });

  function onError(e) {
    console.error(e.message || e);
    return cb ? cb(e.message || e) : false;
  }

  child.once('error', onError);

  child.unref();

  child.once('message', function(msg) {
    debug('PM2 daemon launched with return message: ', msg);
    child.removeListener('error', onError);
    child.disconnect();

    if (opts && opts.interactor == false)
      return cb(null, child);

    /**
     * Here the Keymetrics agent is launched automaticcaly if
     * it has been already configured before (via pm2 link)
     */
    KMDaemon.launchAndInteract(that.conf, {
      machine_name : that.machine_name,
      public_key   : that.public_key,
      secret_key   : that.secret_key
    }, function(err, data, interactor_proc) {
      that.interactor_process = interactor_proc;
      return cb(null, child);
    });
  });
}
```
- example usage
```shell
...
  });
  return false;
}

/**
 * Daemon mode
 */
that.launchDaemon(function(err, child) {
  if (err) {
    Common.printError(err);
    return cb ? cb(err) : process.exit(that.conf.ERROR_EXIT);
  }
  Common.printOut(that.conf.PREFIX_MSG + 'PM2 Successfully daemonized');
  that.launchRPC(function(err, meta) {
    return cb(null, {
...
```

#### <a name="apidoc.element.pm2.Client.prototype.launchRPC"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>launchRPC (cb)](#apidoc.element.pm2.Client.prototype.launchRPC)
- description and source-code
```javascript
function launchRPC(cb) {
  var self = this;
  debug('Launching RPC client on socket file %s', this.rpc_socket_file);
  var req      = axon.socket('req');
  this.client  = new rpc.Client(req);

  this.client.sock.once('connect', function() {
    // Avoid keeping the event loop busy if no more items running
    // if (req && req.socks && req.socks[0] && req.socks[0].unref &&
    //     self.conf.PM2_PROGRAMMATIC)
    //   req.socks[0].unref();
    debug('RPC Connected to Daemon');
    //process.emit('satan:client:ready');
    setTimeout(function() {
      return cb ? cb(null) : false;
    }, 4);
  });

  this.client.sock.on('error', function(e) {
    return cb(e);
  });

  this.client_sock = req.connect(this.rpc_socket_file);
}
```
- example usage
```shell
...
// @breaking change (noDaemonMode has been drop)
// @todo ret err
Client.prototype.start = function(cb) {
var that = this;

this.pingDaemon(function(daemonAlive) {
  if (daemonAlive == true)
    return that.launchRPC(function(err, meta) {
      return cb(null, {
        daemon_mode      : that.conf.daemon_mode,
        new_pm2_instance : false,
        rpc_socket_file  : that.rpc_socket_file,
        pub_socket_file  : that.pub_socket_file,
        pm2_home         : that.pm2_home
      });
...
```

#### <a name="apidoc.element.pm2.Client.prototype.notifyGod"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>notifyGod (action_name, id, cb)](#apidoc.element.pm2.Client.prototype.notifyGod)
- description and source-code
```javascript
notifyGod = function (action_name, id, cb) {
  this.executeRemote('notifyByProcessId', {
    id : id,
    action_name : action_name,
    manually : true
  }, function() {
    debug('God notified');
    return cb ? cb() : false;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.pingDaemon"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>pingDaemon (cb)](#apidoc.element.pm2.Client.prototype.pingDaemon)
- description and source-code
```javascript
function pingDaemon(cb) {
  var req    = axon.socket('req');
  var client = new rpc.Client(req);

  debug('[PING PM2] Trying to connect to server');

  client.sock.once('reconnect attempt', function() {
    client.sock.close();
    debug('Daemon not launched');
    process.nextTick(function() {
      return cb(false);
    });
  });

  client.sock.once('connect', function() {
    client.sock.once('close', function() {
      return cb(true);
    });
    client.sock.close();
    debug('Daemon alive');
  });

  req.connect(this.rpc_socket_file);
}
```
- example usage
```shell
...
}

// @breaking change (noDaemonMode has been drop)
// @todo ret err
Client.prototype.start = function(cb) {
var that = this;

this.pingDaemon(function(daemonAlive) {
  if (daemonAlive == true)
    return that.launchRPC(function(err, meta) {
      return cb(null, {
        daemon_mode      : that.conf.daemon_mode,
        new_pm2_instance : false,
        rpc_socket_file  : that.rpc_socket_file,
        pub_socket_file  : that.pub_socket_file,
...
```

#### <a name="apidoc.element.pm2.Client.prototype.start"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>start (cb)](#apidoc.element.pm2.Client.prototype.start)
- description and source-code
```javascript
start = function (cb) {
  var that = this;

  this.pingDaemon(function(daemonAlive) {
    if (daemonAlive == true)
      return that.launchRPC(function(err, meta) {
        return cb(null, {
          daemon_mode      : that.conf.daemon_mode,
          new_pm2_instance : false,
          rpc_socket_file  : that.rpc_socket_file,
          pub_socket_file  : that.pub_socket_file,
          pm2_home         : that.pm2_home
        });
      });

<span class="apidocCodeCommentSpan">    /**
     * No Daemon mode
     */
</span>    if (that.daemon_mode == false) {
      var Daemon         = require('./Daemon.js');

      var daemon = new Daemon({
        pub_socket_file : that.conf.DAEMON_PUB_PORT,
        rpc_socket_file : that.conf.DAEMON_RPC_PORT,
        pid_file        : that.conf.PM2_PID_FILE_PATH
      });

      console.log('Launching in no daemon mode');

      daemon.innerStart(function() {
        KMDaemon.launchAndInteract(that.conf, {
          machine_name : that.machine_name,
          public_key   : that.public_key,
          secret_key   : that.secret_key
        }, function(err, data, interactor_proc) {
          that.interactor_process = interactor_proc;
        });

        that.launchRPC(function(err, meta) {
          return cb(null, {
            daemon_mode      : that.conf.daemon_mode,
            new_pm2_instance : false,
            rpc_socket_file  : that.rpc_socket_file,
            pub_socket_file  : that.pub_socket_file,
            pm2_home         : that.pm2_home
          });
        });
      });
      return false;
    }

    /**
     * Daemon mode
     */
    that.launchDaemon(function(err, child) {
      if (err) {
        Common.printError(err);
        return cb ? cb(err) : process.exit(that.conf.ERROR_EXIT);
      }
      Common.printOut(that.conf.PREFIX_MSG + 'PM2 Successfully daemonized');
      that.launchRPC(function(err, meta) {
        return cb(null, {
          daemon_mode      : that.conf.daemon_mode,
          new_pm2_instance : true,
          rpc_socket_file  : that.rpc_socket_file,
          pub_socket_file  : that.pub_socket_file,
          pm2_home         : that.pm2_home
        });
      });
    });
  });
}
```
- example usage
```shell
...
}
else if (method.indexOf('restartProcessId') !== -1 && process.argv.indexOf('--watch') > -1) {
  delete app_conf.env.current_conf.watch;
  this.toggleWatch(method, app_conf);
}

if (!this.client || !this.client.call) {
  this.start(function(error) {
    if (error) {
      if (fn)
        return fn(error);
      console.error(error);
      return process.exit(0);
    }
    return self.client.call(method, app_conf, fn);
...
```

#### <a name="apidoc.element.pm2.Client.prototype.startWatch"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>startWatch (method, env, fn)](#apidoc.element.pm2.Client.prototype.startWatch)
- description and source-code
```javascript
function restartWatch(method, env, fn) {
  debug('Calling startWatch');
  this.client.call('startWatch', method, env, function() {
    return fn ? fn() : false;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Client.prototype.stopWatch"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>stopWatch (method, env, fn)](#apidoc.element.pm2.Client.prototype.stopWatch)
- description and source-code
```javascript
function stopWatch(method, env, fn) {
  debug('Calling stopWatch');
  this.client.call('stopWatch', method, env, function() {
    return fn ? fn() : false;
  });
}
```
- example usage
```shell
...
 * @return
 */
Client.prototype.executeRemote = function executeRemote(method, app_conf, fn) {
var self = this;

// stop watch on stop | env is the process id
if (method.indexOf('stop') !== -1) {
  this.stopWatch(method, app_conf);
}
// stop watching when process is deleted
else if (method.indexOf('delete') !== -1) {
  this.stopWatch(method, app_conf);
}
// stop everything on kill
else if (method.indexOf('kill') !== -1) {
...
```

#### <a name="apidoc.element.pm2.Client.prototype.toggleWatch"></a>[function <span class="apidocSignatureSpan">pm2.Client.prototype.</span>toggleWatch (method, env, fn)](#apidoc.element.pm2.Client.prototype.toggleWatch)
- description and source-code
```javascript
function toggleWatch(method, env, fn) {
  debug('Calling toggleWatch');
  this.client.call('toggleWatch', method, env, function() {
    return fn ? fn() : false;
  });
}
```
- example usage
```shell
...
}
// stop everything on kill
else if (method.indexOf('kill') !== -1) {
  this.stopWatch('deleteAll', app_conf);
}
else if (method.indexOf('restartProcessId') !== -1 && process.argv.indexOf('--watch') > -1) {
  delete app_conf.env.current_conf.watch;
  this.toggleWatch(method, app_conf);
}

if (!this.client || !this.client.call) {
  this.start(function(error) {
    if (error) {
      if (fn)
        return fn(error);
...
```



# <a name="apidoc.module.pm2.Common"></a>[module pm2.Common](#apidoc.module.pm2.Common)

#### <a name="apidoc.element.pm2.Common.clone"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>clone (obj)](#apidoc.element.pm2.Common.clone)
- description and source-code
```javascript
clone = function (obj) {
  if (obj === null || obj === undefined) return {};
  return fclone(obj);
}
```
- example usage
```shell
...

  try {
    // Application Name nverride
    if (msg.data.name)
      God.clusters_db[msg.process.pm_id].pm2_env.name = msg.data.name;

    Object.keys(msg.data).forEach(function(conf_key) {
      God.clusters_db[msg.process.pm_id].pm2_env.axm_options[conf_key] = Utility.clone(msg.data[conf_key]);
    });
  } catch(e) {
    console.error(e.stack || e);
  }
  msg = null;
});
...
```

#### <a name="apidoc.element.pm2.Common.deepCopy"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>deepCopy (obj)](#apidoc.element.pm2.Common.deepCopy)
- description and source-code
```javascript
deepCopy = function (obj) {
  if (obj === null || obj === undefined) return {};
  return fclone(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Common.extend"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>extend (destination, source)](#apidoc.element.pm2.Common.extend)
- description and source-code
```javascript
extend = function (destination, source){
  if (!source || typeof source != 'object') return destination;

  Object.keys(source).forEach(function(new_key) {
    if (source[new_key] != '[object Object]')
      destination[new_key] = source[new_key];
  });

  return destination;
}
```
- example usage
```shell
...

var Utility = module.exports = {
getDate : function() {
  return Date.now();
},
extendExtraConfig : function(proc, opts) {
  if (opts.env && opts.env.current_conf) {
    Utility.extend(proc.pm2_env, opts.env.current_conf);
    delete opts.env.current_conf;
  }
},
formatCLU : function(process) {
  if (!process.pm2_env) {
    return process;
  }
...
```

#### <a name="apidoc.element.pm2.Common.isConfigFile"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>isConfigFile (filename)](#apidoc.element.pm2.Common.isConfigFile)
- description and source-code
```javascript
isConfigFile = function (filename) {
  if (typeof(filename) != 'string')
    return null;
  if (filename.indexOf('.json') != -1)
    return 'json';
  if (filename.indexOf('.yml') > -1 || filename.indexOf('.yaml') > -1)
    return 'yaml';
  if (filename.indexOf('.config.js') != -1)
    return 'js';
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Common.mergeEnvironmentVariables"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>mergeEnvironmentVariables (app_env, env_name, deploy_conf)](#apidoc.element.pm2.Common.mergeEnvironmentVariables)
- description and source-code
```javascript
mergeEnvironmentVariables = function (app_env, env_name, deploy_conf) {
  var app = fclone(app_env);

  if (!app.env)
    app.env = {};

  if (env_name) {
    var finalEnv = {};

    // First merge variables from deploy.production.env object as least priority.
    if (deploy_conf && deploy_conf[env_name] && deploy_conf[env_name]['env']) {
      util._extend(finalEnv, deploy_conf[env_name]['env']);
    }

    // Then merge app.env object.
    util._extend(finalEnv, app.env);

    // Then, last and highest priority, merge the app.env_production object.
    if ('env_' + env_name in app) {
      util._extend(finalEnv, app['env_' + env_name]);
    }

    app.env = finalEnv;
  }

  for (var key in app.env) {
    if (typeof app.env[key] == 'object') {
      app.env[key] = JSON.stringify(app.env[key]);
    }
  }

<span class="apidocCodeCommentSpan">  /**
   * Extra configuration update
   */
</span>  var current_conf = fclone(app);
  delete current_conf.env;
  app.env.current_conf = current_conf;

  // #2541 force resolution of node interpreter
  if (app.env.current_conf.exec_interpreter &&
      app.env.current_conf.exec_interpreter.indexOf('@') > -1)
    resolveNodeInterpreter(app.env.current_conf);

  return app.env;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Common.parseConfig"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>parseConfig (confObj, filename)](#apidoc.element.pm2.Common.parseConfig)
- description and source-code
```javascript
parseConfig = function (confObj, filename) {
  var yamljs = require('yamljs');
  var vm     = require('vm');

  if (!filename || filename == 'pipe' || filename == 'none' ||
      filename.indexOf('.json') > -1) {
    var code = '(' + confObj + ')';
    var sandbox = {};
    if (semver.satisfies(process.version, '>= 0.12.0')) {
      return vm.runInThisContext(code, sandbox, {
        filename: path.resolve(filename),
        displayErrors: false,
        timeout: 1000
      });
    } else {
      // Use the Node 0.10 API
      return vm.runInNewContext(code, sandbox, filename);
    }
  }
  else if (filename.indexOf('.yml') > -1 ||
           filename.indexOf('.yaml') > -1) {
    return yamljs.parse(confObj.toString());
  }
  else if (filename.indexOf('.config.js') > -1) {
    var confPath = require.resolve(path.resolve(filename));
    delete require.cache[confPath];
    return require(confPath);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Common.prepareAppConf"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>prepareAppConf (opts, app)](#apidoc.element.pm2.Common.prepareAppConf)
- description and source-code
```javascript
prepareAppConf = function (opts, app) {
<span class="apidocCodeCommentSpan">  /**
   * Minimum validation
   */
</span>  if (!app.script)
    return new Error('No script path - aborting');

  // Forbidden application name
  if (app.name == 'push')
    return new Error('Push application name is not allowed');

  if (app.automation == false)
    app.pmx = false;

  if (!app.node_args)
    app.node_args = [];

  if (app.port && app.env)
    app.env.PORT = app.port;

  // CRON
  var ret;
  if ((ret = Common.sink.determineCron(app)) instanceof Error)
    return ret;

  // Resolve paths
  // app.pm_exec_path = path.join(resolveCWD(app.cwd, opts.cwd), app.script);
  // app.pm_cwd = path.dirname(app.pm_exec_path);
  // console.log(' hads', app.pm_cwd);
  var cwd = null;

  if (app.cwd) {
    cwd = path.resolve(app.cwd);
    process.env.PWD = app.cwd;
  }

  // CWD option resolving
  cwd && (cwd[0] != '/') && (cwd = path.resolve(process.cwd(), cwd));
  cwd = cwd || opts.cwd;

  // Full path script resolution
  app.pm_exec_path = path.resolve(cwd, app.script);


  // If script does not exists after resolution
  if (!fs.existsSync(app.pm_exec_path)) {
    var ckd;
    // Try resolve command available in $PATH
    if ((ckd = shelljs.which(app.script))) {
      if (typeof(ckd) !== 'string')
        ckd = ckd.toString();
      app.pm_exec_path = ckd;
    }
    else
      // Throw critical error
      return new Error('script not found : ' + app.pm_exec_path);
  }

  /**
   * Auto detect .map file and enable source map support automatically
   */
  if (app.disable_source_map_support != true) {
    try {
      if (fs.accessSync) {
        fs.accessSync(app.pm_exec_path + '.map', fs.R_OK);
        app.source_map_support = true;
      }
      else {
        // Support for Node 0.10.x
        if (fs.existsSync(app.pm_exec_path + '.map')) {
          app.source_map_support = true;
        }
      }
    } catch(e) {}
    delete app.disable_source_map_support;
  }

  delete app.script;

  // Set current env by first adding the process environment and then extending/replacing it
  // with env specified on command-line or JSON file.

  var env = {};

  /**
   * Do not copy internal pm2 environment variables if acting on process
   * is made from a programmatic script started by PM2
   */
  if (cst.PM2_PROGRAMMATIC)
    Common.safeExtend(env, process.env);
  else
    env = process.env;

  // Change to double check  (dropped , {pm_cwd: cwd})
  app.env = [{}, env, app.env || {}].reduce(function(e1, e2){
    return util._extend(e1, e2);
  });

  app.pm_cwd = cwd;
  // Interpreter
  Common.sink.resolveInterpreter(app);

  // Exec mode and cluster stuff
  Common.sink.determineExecMode(app);

  /**
   * Scary
   */
  var formated_app_name = app.name.replace(/[^a-zA-Z0-9\\.\\-]/g, '-');

  ['log', 'out', 'error', 'pid'].forEach(function(f){
    var af = app[f + '_file'], ps, ext = (f == 'pid' ? 'pid':'log'), isStd = !~['log', 'pid'].indexOf(f);
    if (af) af = resolveHome(af);

    if ((f == 'log' && typeof af == 'boolean' && af) || (f != 'log' && !af)) {
      ps = [cst['DEFAULT_' + ext.toUpperCase() + '_PATH'], formated_app_name + (isStd ? '-' + f : '') + '.' + ext];
    } else if (f != 'log' || (f == 'log' && af)) {
      ps = [cwd, af];

      var dir = path.dirname(path.resolve(cwd, af));
      if (!fs.existsSync(dir)) {
        Common.printError(cst.PREFIX_MSG_WARNING + 'Folder does not exists: ' + dir);
        Common.printOut(cst.PREFIX_MSG + 'Creating folder: ' + dir);
        mkdirp(dir, function(err) {
          if (!err) return;
          Common.printError(cst.PREFIX_MSG_ERR + 'Could not create folder: ' + path.dirname(af));
          throw new Error('Could not create folder');
        });
      }

    }
    // PM2 paths
    ps && (app['pm_' + (isStd ? f.substr(0, 3) + '_' : '') + ext + '_path'] = path.resolve.apply(null, ps));
    delete app[f + '_file'];
  });

  return app;
}
```
- example usage
```shell
...
 * @param {Object} opts.pm2_home
 * @param {Object} appConf application configuration
 * @return app
 */
Common.resolveAppAttributes = function(opts, legacy_app) {
  var appConf = fclone(legacy_app);

  var app = Common.prepareAppConf(opts, appConf);
  if (app instanceof Error) {
    Common.printError(cst.PREFIX_MSG_ERR + app.message);
    throw new Error(app.message);
  }
  return app;
}
...
```

#### <a name="apidoc.element.pm2.Common.printError"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>printError (msg)](#apidoc.element.pm2.Common.printError)
- description and source-code
```javascript
printError = function (msg) {
  if (process.env.PM2_SILENT || process.env.PM2_PROGRAMMATIC === 'true') return false;
  if (msg instanceof Error)
    return console.error(msg.message);
  return console.error.apply(console, arguments);
}
```
- example usage
```shell
...
}

/**
 * Daemon mode
 */
that.launchDaemon(function(err, child) {
  if (err) {
    Common.printError(err);
    return cb ? cb(err) : process.exit(that.conf.ERROR_EXIT);
  }
  Common.printOut(that.conf.PREFIX_MSG + 'PM2 Successfully daemonized');
  that.launchRPC(function(err, meta) {
    return cb(null, {
      daemon_mode      : that.conf.daemon_mode,
      new_pm2_instance : true,
...
```

#### <a name="apidoc.element.pm2.Common.printOut"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>printOut ()](#apidoc.element.pm2.Common.printOut)
- description and source-code
```javascript
printOut = function () {
  if (process.env.PM2_SILENT === 'true' || process.env.PM2_PROGRAMMATIC === 'true') return false;
  return console.log.apply(console, arguments);
}
```
- example usage
```shell
...
 * Daemon mode
 */
that.launchDaemon(function(err, child) {
  if (err) {
    Common.printError(err);
    return cb ? cb(err) : process.exit(that.conf.ERROR_EXIT);
  }
  Common.printOut(that.conf.PREFIX_MSG + 'PM2 Successfully daemonized');
  that.launchRPC(function(err, meta) {
    return cb(null, {
      daemon_mode      : that.conf.daemon_mode,
      new_pm2_instance : true,
      rpc_socket_file  : that.rpc_socket_file,
      pub_socket_file  : that.pub_socket_file,
      pm2_home         : that.pm2_home
...
```

#### <a name="apidoc.element.pm2.Common.resolveAppAttributes"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>resolveAppAttributes (opts, legacy_app)](#apidoc.element.pm2.Common.resolveAppAttributes)
- description and source-code
```javascript
resolveAppAttributes = function (opts, legacy_app) {
  var appConf = fclone(legacy_app);

  var app = Common.prepareAppConf(opts, appConf);
  if (app instanceof Error) {
    Common.printError(cst.PREFIX_MSG_ERR + app.message);
    throw new Error(app.message);
  }
  return app;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Common.retErr"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>retErr (e)](#apidoc.element.pm2.Common.retErr)
- description and source-code
```javascript
retErr = function (e) {
  if (!e)
    return new Error('Unidentified error');
  if (e instanceof Error)
    return e;
  return new Error(e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Common.safeExtend"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>safeExtend (origin, add)](#apidoc.element.pm2.Common.safeExtend)
- description and source-code
```javascript
safeExtend = function (origin, add){
  if (!add || typeof add != 'object') return origin;

  //Ignore PM2's set environment variables from the nested env
  var keysToIgnore = ['name', 'exec_mode', 'env', 'args', 'pm_cwd', 'exec_interpreter', 'pm_exec_path', 'node_args', 'pm_out_log_path
', 'pm_err_log_path', 'pm_pid_path', 'pm_id', 'status', 'pm_uptime', 'created_at', 'unstable_restarts', 'restart_time', 'axm_actions
', 'pmx_module', 'command', 'watch', 'versioning', 'vizion_runing', 'MODULE_DEBUG', 'pmx', 'axm_options', 'created_at', 'watch', '
vizion', 'axm_dynamic', 'axm_monitor', 'instances', 'automation', 'autorestart', 'node_args', 'unstable_restart', 'treekill', 'exit_code
'];

  var keys = Object.keys(add);
  var i = keys.length;
  while (i--) {
  	//Only copy stuff into the env that we don't have already.
  	if(keysToIgnore.indexOf(keys[i]) == -1 && add[keys[i]] != '[object Object]')
      origin[keys[i]] = add[keys[i]];
  }
  return origin;
}
```
- example usage
```shell
...
var env = {};

/**
 * Do not copy internal pm2 environment variables if acting on process
 * is made from a programmatic script started by PM2
 */
if (cst.PM2_PROGRAMMATIC)
  Common.safeExtend(env, process.env);
else
  env = process.env;

// Change to double check  (dropped , {pm_cwd: cwd})
app.env = [{}, env, app.env || {}].reduce(function(e1, e2){
  return util._extend(e1, e2);
});
...
```

#### <a name="apidoc.element.pm2.Common.serialize"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>serialize (obj)](#apidoc.element.pm2.Common.serialize)
- description and source-code
```javascript
serialize = function (obj) {
  if (obj === null || obj === undefined) return {};
  return fclone(obj);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Common.verifyConfs"></a>[function <span class="apidocSignatureSpan">pm2.Common.</span>verifyConfs (appConfs)](#apidoc.element.pm2.Common.verifyConfs)
- description and source-code
```javascript
verifyConfs = function (appConfs){
  if (!appConfs || appConfs.length == 0){
    return [];
  }

  // Make sure it is an Array.
  appConfs = [].concat(appConfs);

  var verifiedConf = [];

  for (var i = 0; i < appConfs.length; i++) {
    var app = appConfs[i];

    if (app.disable_trace) {
      app.trace = false
      delete app.disable_trace;
    }

    // Warn deprecates.
    checkDeprecates(app);

    // Check Exec mode
    checkExecMode(app);

    // Render an app name if not existing.
    prepareAppName(app);

    var ret = Config.validateJSON(app);
    //debug('After processing', ret);
    // Show errors if existing.

    if (ret.errors && ret.errors.length > 0){
      ret.errors.forEach(function(err){
        warn(err);
      });
      // Return null == error
      return new Error(ret.errors);
    }
    verifiedConf.push(ret.config);
  }

  return verifiedConf;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pm2.Configuration"></a>[module pm2.Configuration](#apidoc.module.pm2.Configuration)

#### <a name="apidoc.element.pm2.Configuration.get"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>get (key, cb)](#apidoc.element.pm2.Configuration.get)
- description and source-code
```javascript
get = function (key, cb) {
  Configuration.getAll(function(err, data) {
    var climb = splitKey(key);

    climb.some(function(val) {
      if (!data[val]) {
        data = null;
        return true;
      }
      data = data[val];
      return false;
    });

    if (!data) return cb({err : 'Unknown key'}, null);
    return cb(null, data);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Configuration.getAll"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>getAll (cb)](#apidoc.element.pm2.Configuration.getAll)
- description and source-code
```javascript
getAll = function (cb) {
  fs.readFile(cst.PM2_MODULE_CONF_FILE, function(err, data) {
    if (err) return cb(err);
    return cb(null, JSON.parse(data));
  });
}
```
- example usage
```shell
...

  async.eachSeries(arrays, function(el, next) {
Configuration.set(el[0], el[1], next);
  }, cb);
};

Configuration.get = function(key, cb) {
  Configuration.getAll(function(err, data) {
var climb = splitKey(key);

climb.some(function(val) {
  if (!data[val]) {
    data = null;
    return true;
  }
...
```

#### <a name="apidoc.element.pm2.Configuration.getAllSync"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>getAllSync ()](#apidoc.element.pm2.Configuration.getAllSync)
- description and source-code
```javascript
getAllSync = function () {
  try {
    return JSON.parse(fs.readFileSync(cst.PM2_MODULE_CONF_FILE));
  } catch(e) {
    console.error(e.stack || e);
    return {};
  }
}
```
- example usage
```shell
...
  if (!data) return cb({err : 'Unknown key'}, null);
  return cb(null, data);
});
};

Configuration.getSync = function(key) {
try {
  var data = Configuration.getAllSync();
} catch(e) {
  return null;
}

var climb = splitKey(key);

climb.some(function(val) {
...
```

#### <a name="apidoc.element.pm2.Configuration.getSync"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>getSync (key)](#apidoc.element.pm2.Configuration.getSync)
- description and source-code
```javascript
getSync = function (key) {
  try {
    var data = Configuration.getAllSync();
  } catch(e) {
    return null;
  }

  var climb = splitKey(key);

  climb.some(function(val) {
    if (!data[val]) {
      data = null;
      return true;
    }
    data = data[val];
    return false;
  });

  if (!data) return null;
  return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Configuration.multiset"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>multiset (serial, cb)](#apidoc.element.pm2.Configuration.multiset)
- description and source-code
```javascript
multiset = function (serial, cb) {
  var arrays = [];
  serial = serial.match(/(?:[^ "]+|"[^"]*")+/g);

  while (serial.length > 0)
    arrays.push(serial.splice(0, 2));

  async.eachSeries(arrays, function(el, next) {
    Configuration.set(el[0], el[1], next);
  }, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Configuration.set"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>set (key, value, cb)](#apidoc.element.pm2.Configuration.set)
- description and source-code
```javascript
set = function (key, value, cb) {
  fs.readFile(cst.PM2_MODULE_CONF_FILE, function(err, data) {
    if (err) return cb(err);

    var json_conf = JSON.parse(data);

    var values = splitKey(key);

    if (values.length > 0) {
      var levels = values;

      var tmp = json_conf;

      levels.forEach(function(key, index) {
        if (index == levels.length -1)
          tmp[key] = value;
        else if (!tmp[key]) {
          tmp[key] = {};
          tmp = tmp[key];
        }
        else {
          if (typeof(tmp[key]) != 'object')
            tmp[key] = {};
          tmp = tmp[key];
        }
      });

    }
    else {
      if (json_conf[key] && typeof(json_conf[key]) === 'string')
        Common.printOut(cst.PREFIX_MSG + 'Replacing current value key %s by %s', key, value);

      json_conf[key] = value;
    }

    fs.writeFile(cst.PM2_MODULE_CONF_FILE, JSON.stringify(json_conf, null, 4), function(err, data) {
      if (err) return cb(err);

      return cb(null, json_conf);
    });
    return false;
  });
}
```
- example usage
```shell
...
var arrays = [];
serial = serial.match(/(?:[^ "]+|"[^"]*")+/g);

while (serial.length > 0)
  arrays.push(serial.splice(0, 2));

async.eachSeries(arrays, function(el, next) {
  Configuration.set(el[0], el[1], next);
}, cb);
};

Configuration.get = function(key, cb) {
Configuration.getAll(function(err, data) {
  var climb = splitKey(key);
...
```

#### <a name="apidoc.element.pm2.Configuration.setSync"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>setSync (key, value)](#apidoc.element.pm2.Configuration.setSync)
- description and source-code
```javascript
setSync = function (key, value) {
  try {
    var data = fs.readFileSync(cst.PM2_MODULE_CONF_FILE);
  } catch(e) {
    return null;
  }

  var json_conf = JSON.parse(data);

  var values = splitKey(key);

  if (values.length > 0) {
    var levels = values;

    var tmp = json_conf;

    levels.forEach(function(key, index) {
      if (index == levels.length -1)
        tmp[key] = value;
      else if (!tmp[key]) {
        tmp[key] = {};
        tmp = tmp[key];
      }
      else {
        if (typeof(tmp[key]) != 'object')
          tmp[key] = {};
        tmp = tmp[key];
      }
    });

  }
  else {
    if (json_conf[key] && typeof(json_conf[key]) === 'string')
      Common.printOut(cst.PREFIX_MSG + 'Replacing current value key %s by %s', key, value);

    json_conf[key] = value;
  }

  if (key === 'all')
    json_conf = {};

  try {
    fs.writeFileSync(cst.PM2_MODULE_CONF_FILE, JSON.stringify(json_conf));
    return json_conf;
  } catch(e) {
    console.error(e.message);
    return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Configuration.unset"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>unset (key, cb)](#apidoc.element.pm2.Configuration.unset)
- description and source-code
```javascript
unset = function (key, cb) {
  fs.readFile(cst.PM2_MODULE_CONF_FILE, function(err, data) {
    if (err) return cb(err);

    var json_conf = JSON.parse(data);

    var values = splitKey(key);

    if (values.length > 0) {
      var levels = values;

      var tmp = json_conf;

      levels.forEach(function(key, index) {
        if (index == levels.length -1)
          delete tmp[key];
        else if (!tmp[key]) {
          tmp[key] = {};
          tmp = tmp[key];
        }
        else {
          if (typeof(tmp[key]) != 'object')
            tmp[key] = {};
          tmp = tmp[key];
        }
      });

    }
    else
      delete json_conf[key];

    if (err) return cb(err);

    if (key === 'all')
      json_conf = {};

    fs.writeFile(cst.PM2_MODULE_CONF_FILE, JSON.stringify(json_conf), function(err, data) {
      if (err) return cb(err);

      return cb(null, json_conf);
    });
    return false;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Configuration.unsetSync"></a>[function <span class="apidocSignatureSpan">pm2.Configuration.</span>unsetSync (key)](#apidoc.element.pm2.Configuration.unsetSync)
- description and source-code
```javascript
unsetSync = function (key) {
  try {
    var data = fs.readFileSync(cst.PM2_MODULE_CONF_FILE);
  } catch(e) {
    return null;
  }

  var json_conf = JSON.parse(data);

  var values = splitKey(key);

  if (values.length > 0) {
    var levels = values;

    var tmp = json_conf;

    levels.forEach(function(key, index) {
      if (index == levels.length -1)
        delete tmp[key];
      else if (!tmp[key]) {
        tmp[key] = {};
        tmp = tmp[key];
      }
      else {
        if (typeof(tmp[key]) != 'object')
          tmp[key] = {};
        tmp = tmp[key];
      }
    });

  }
  else
    delete json_conf[key];

  if (key === 'all')
    json_conf = {};

  try {
    fs.writeFileSync(cst.PM2_MODULE_CONF_FILE, JSON.stringify(json_conf));
  } catch(e) {
    console.error(e.message);
    return null;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pm2.Daemon"></a>[module pm2.Daemon](#apidoc.module.pm2.Daemon)

#### <a name="apidoc.element.pm2.Daemon.Daemon"></a>[function <span class="apidocSignatureSpan">pm2.</span>Daemon (opts)](#apidoc.element.pm2.Daemon.Daemon)
- description and source-code
```javascript
Daemon = function (opts) {
  if (!opts) opts = {};

  this.rpc_socket_ready = false;
  this.pub_socket_ready = false;

  this.pub_socket_file = opts.pub_socket_file || cst.DAEMON_PUB_PORT;
  this.rpc_socket_file = opts.rpc_socket_file || cst.DAEMON_RPC_PORT;

  this.pid_path        = opts.pid_file || cst.PM2_PID_FILE_PATH;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pm2.Daemon.prototype"></a>[module pm2.Daemon.prototype](#apidoc.module.pm2.Daemon.prototype)

#### <a name="apidoc.element.pm2.Daemon.prototype.close"></a>[function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>close (opts, cb)](#apidoc.element.pm2.Daemon.prototype.close)
- description and source-code
```javascript
close = function (opts, cb) {
  var that = this;

  God.bus.emit('pm2:kill', {
    status : 'killed',
    msg    : 'pm2 has been killed via CLI'
  });

  fmt.sep();
  fmt.title('Stopping PM2');
  fmt.field('Time', new Date());
  fmt.sep();

<span class="apidocCodeCommentSpan">  /**
   * Cleanly kill pm2
   */
</span>  that.rpc_socket.close(function() {
    console.log('RPC closed');
    that.pub_socket.close(function() {
      console.log('PUB closed');

      // notify cli that the daemon is shuting down (only under unix since windows doesnt handle signals)
      if (cst.IS_WINDOWS === false) {
        try {
          process.kill(parseInt(opts.pid), 'SIGQUIT');
        } catch(e) {
          console.error('Could not send SIGQUIT to CLI');
        }
      }

      console.log('PM2 successfully stopped');
      setTimeout(function() {
        process.exit(cst.SUCCESS_EXIT);
      }, 2);
    });
  });
}
```
- example usage
```shell
...
Client.prototype.pingDaemon = function pingDaemon(cb) {
var req    = axon.socket('req');
var client = new rpc.Client(req);

debug('[PING PM2] Trying to connect to server');

client.sock.once('reconnect attempt', function() {
  client.sock.close();
  debug('Daemon not launched');
  process.nextTick(function() {
    return cb(false);
  });
});

client.sock.once('connect', function() {
...
```

#### <a name="apidoc.element.pm2.Daemon.prototype.gracefullExit"></a>[function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>gracefullExit ()](#apidoc.element.pm2.Daemon.prototype.gracefullExit)
- description and source-code
```javascript
gracefullExit = function () {
  var that = this;

  console.log('pm2 has been killed by signal, dumping process list before exit...');

  God.dumpProcessList(function() {

    var processes = God.getFormatedProcesses();

    async.eachLimit(processes, 1, function(proc, next) {
      console.log('Deleting process %s', proc.pm2_env.pm_id);
      God.deleteProcessId(proc.pm2_env.pm_id, function() {
        return next();
      });
      return false;
    }, function(err) {
      try {
        fs.unlinkSync(that.pid_path);
      } catch(e) {}
      console.log('[PM2] Exited peacefully');
      process.exit(0);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Daemon.prototype.handleSignals"></a>[function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>handleSignals ()](#apidoc.element.pm2.Daemon.prototype.handleSignals)
- description and source-code
```javascript
handleSignals = function () {
  var that = this;

  process.on('SIGTERM', that.gracefullExit);
  process.on('SIGINT', that.gracefullExit);
  process.on('SIGHUP', function() {});
  process.on('SIGQUIT', that.gracefullExit);
  process.on('SIGUSR2', function() {
    God.reloadLogs({}, function() {});
  });
}
```
- example usage
```shell
...
// Write Daemon PID into file
try {
  fs.writeFileSync(that.pid_path, process.pid);
} catch (e) {
  console.error(e.stack || e);
}

this.handleSignals();

/**
 * Pub system for real time notifications
 */
this.pub    = axon.socket('pub-emitter');

this.pub_socket = this.pub.bind(this.pub_socket_file);
...
```

#### <a name="apidoc.element.pm2.Daemon.prototype.innerStart"></a>[function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>innerStart (cb)](#apidoc.element.pm2.Daemon.prototype.innerStart)
- description and source-code
```javascript
innerStart = function (cb) {
  var that = this;

  if (!cb) cb = function() {
    fmt.sep();
    fmt.title('New PM2 Daemon started');
    fmt.field('Time', new Date());
    fmt.field('PM2 version', pkg.version);
    fmt.field('Node.js version', process.versions.node);
    fmt.field('Current arch', process.arch);
    fmt.field('PM2 home', cst.PM2_HOME);
    fmt.field('PM2 PID file', that.pid_path);
    fmt.field('RPC socket file', that.rpc_socket_file);
    fmt.field('BUS socket file', that.pub_socket_file);
    fmt.field('Application log path', cst.DEFAULT_LOG_PATH);
    fmt.field('Process dump file', cst.DUMP_FILE_PATH);
    fmt.field('Concurrent actions', cst.CONCURRENT_ACTIONS);
    fmt.field('SIGTERM timeout', cst.KILL_TIMEOUT);
    fmt.sep();
  };

  // Write Daemon PID into file
  try {
    fs.writeFileSync(that.pid_path, process.pid);
  } catch (e) {
    console.error(e.stack || e);
  }

  this.handleSignals();

<span class="apidocCodeCommentSpan">  /**
   * Pub system for real time notifications
   */
</span>  this.pub    = axon.socket('pub-emitter');

  this.pub_socket = this.pub.bind(this.pub_socket_file);

  this.pub_socket.once('bind', function() {
    that.pub_socket_ready = true;
    that.sendReady(cb);
  });

  /**
   * Rep/Req - RPC system to interact with God
   */
  this.rep    = axon.socket('rep');

  var server = new rpc.Server(this.rep);

  this.rpc_socket = this.rep.bind(this.rpc_socket_file);

  this.rpc_socket.once('bind', function() {
    that.rpc_socket_ready = true;
    that.sendReady(cb);
  });

  var profiler;

  try {
    profiler = require('v8-profiler');
  } catch(e) {
    profiler = null;
  }

  /**
   * Memory Snapshot
   */
  function snapshotPM2(msg, cb) {
    if (profiler == null) {
      console.log('v8-profiler is not available');
      return cb(new Error('v8-profiler is not available'));
    }

    var snapshot1 = profiler.takeSnapshot();
    var path = require('path');
    snapshot1.export(function(error, result) {
      fs.writeFile(msg.pwd, result, function() {
        snapshot1.delete();
        return cb(null, {file : msg.pwd});
      });
    });
  }

  function startProfilingPM2(msg, cb) {
    if (profiler == null) {
      console.log('v8-profiler is not available');
      return cb(new Error('v8-profiler is not available'));
    }

    profiler.startProfiling('cpu');

    process.nextTick(function() {
      return cb(null, {msg : 'profiling started'});
    });
  }

  function stopProfilingPM2(msg, cb) {
    if (profiler == null) {
      console.log('v8-profiler is not available');
      return cb(new Error('v8-profiler is not available'));
    }

    var profile1 = profiler.stopProfiling('cpu');

    profile1.export()
      .pipe(fs.createWriteStream(msg.pwd))
      .on('finish', function() {
        profile1.delete();
        return cb(null, {file : msg.pwd});
      });
  }

  server.expose({
    killMe                  : that.close.bind(this),
    snapshotPM2             : snapshotPM2,
    profileStart            : startProfilingPM2,
    profileStop             : stopProfilingPM2,
    prepare                 : God.prepare,
    getMonitorData          : God.getMonitorData,
    getSystemData           : God.getSystemData,

    startProcessId          : God.startProcessId,
    stopProcessId           : God.stopProcessId,
    restartProcessId        : God.restartProcessId,
    deleteProcessId         : God.deleteProcessId,

    softReloadProcessId     : God.softReloadProcessId,
    reloadProcessId         : God.reloadProcessId,
    duplicateProcessId      : God.duplicateProcessId,
    resetMetaProcessId      : God.resetMetaProcessId,
    stopWatch               : God.stopWatch,
    startWatch              : God.startWatch,
    toggleWatch             : God.toggleWatch,
    notifyByProcessId       : God.notifyByProcessId,

    notifyKillPM2           : God.notifyKillPM2,
    forceGc                 : God.forceGc,

    msgProcess              : God.msgProcess,
    sendDataToProcessId     : God.sendDataToProcessId,
    sendSignalToProcessId   : God.sendSignalToProcessId,
    sendSignalToProcessName : God.sendSignalToProcessName, ...
```
- example usage
```shell
...
  pub_socket_file : that.conf.DAEMON_PUB_PORT,
  rpc_socket_file : that.conf.DAEMON_RPC_PORT,
  pid_file        : that.conf.PM2_PID_FILE_PATH
});

console.log('Launching in no daemon mode');

daemon.innerStart(function() {
  KMDaemon.launchAndInteract(that.conf, {
    machine_name : that.machine_name,
    public_key   : that.public_key,
    secret_key   : that.secret_key
  }, function(err, data, interactor_proc) {
    that.interactor_process = interactor_proc;
  });
...
```

#### <a name="apidoc.element.pm2.Daemon.prototype.sendReady"></a>[function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>sendReady (cb)](#apidoc.element.pm2.Daemon.prototype.sendReady)
- description and source-code
```javascript
sendReady = function (cb) {
  // Send ready message to Client
  if (this.rpc_socket_ready == true && this.pub_socket_ready == true) {
    cb(null, {
      pid         : process.pid,
      pm2_version : pkg.version
    });
    if (typeof(process.send) != 'function')
      return false;

    process.send({
      online      : true,
      success     : true,
      pid         : process.pid,
      pm2_version : pkg.version
    });
  };
}
```
- example usage
```shell
...
 */
this.pub    = axon.socket('pub-emitter');

this.pub_socket = this.pub.bind(this.pub_socket_file);

this.pub_socket.once('bind', function() {
  that.pub_socket_ready = true;
  that.sendReady(cb);
});

/**
 * Rep/Req - RPC system to interact with God
 */
this.rep    = axon.socket('rep');
...
```

#### <a name="apidoc.element.pm2.Daemon.prototype.start"></a>[function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>start ()](#apidoc.element.pm2.Daemon.prototype.start)
- description and source-code
```javascript
start = function () {
  var that = this;
  var d = domain.create();

  d.once('error', function(err) {
    fmt.sep();
    fmt.title('PM2 global error caught');
    fmt.field('Time', new Date());
    console.error(err.message);
    console.error(err.stack);
    fmt.sep();

    console.error('[PM2][%s] Resurrecting PM2');

		var path = cst.IS_WINDOWS ? process.cwd() + '/bin/pm2' : process.env['_'];
    var fork_new_pm2 = require('child_process').spawn('node', [path, 'update'], {
      detached: true,
      stdio: 'inherit'
    });

    fork_new_pm2.on('close', function() {
      console.log('PM2 successfully forked');
      process.exit(0);
    })

  });

  d.run(function() {
    that.innerStart();
  });
}
```
- example usage
```shell
...
}
else if (method.indexOf('restartProcessId') !== -1 && process.argv.indexOf('--watch') > -1) {
  delete app_conf.env.current_conf.watch;
  this.toggleWatch(method, app_conf);
}

if (!this.client || !this.client.call) {
  this.start(function(error) {
    if (error) {
      if (fn)
        return fn(error);
      console.error(error);
      return process.exit(0);
    }
    return self.client.call(method, app_conf, fn);
...
```

#### <a name="apidoc.element.pm2.Daemon.prototype.startLogic"></a>[function <span class="apidocSignatureSpan">pm2.Daemon.prototype.</span>startLogic ()](#apidoc.element.pm2.Daemon.prototype.startLogic)
- description and source-code
```javascript
startLogic = function () {
  var that = this;

<span class="apidocCodeCommentSpan">  /**
   * Action treatment specifics
   * Attach actions to pm2_env.axm_actions variables (name + options)
   */
</span>  God.bus.on('axm:action', function axmActions(msg) {
    var pm2_env = msg.process;
    var exists  = false;
    var axm_action = msg.data;

    if (!pm2_env || !God.clusters_db[pm2_env.pm_id])
      return console.error('Unknown id %s', pm2_env.pm_id);

    if (!God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions)
      God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions = [];

    God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions.forEach(function(actions) {
      if (actions.action_name == axm_action.action_name)
        exists = true;
    });

    if (exists === false) {
      debug('Adding action', axm_action);
      God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions.push(axm_action);
    }
    msg = null;
  });

  /**
   * Configure module
   */
  God.bus.on('axm:option:configuration', function axmMonitor(msg) {
    if (!msg.process)
      return console.error('[axm:option:configuration] no process defined');

    if (!God.clusters_db[msg.process.pm_id])
      return console.error('[axm:option:configuration] Unknown id %s', msg.process.pm_id);

    try {
      // Application Name nverride
      if (msg.data.name)
        God.clusters_db[msg.process.pm_id].pm2_env.name = msg.data.name;

      Object.keys(msg.data).forEach(function(conf_key) {
        God.clusters_db[msg.process.pm_id].pm2_env.axm_options[conf_key] = Utility.clone(msg.data[conf_key]);
      });
    } catch(e) {
      console.error(e.stack || e);
    }
    msg = null;
  });

  /**
   * Process monitoring data (probes)
   */
  God.bus.on('axm:monitor', function axmMonitor(msg) {
    if (!msg.process)
      return console.error('[axm:monitor] no process defined');

    if (!msg.process || !God.clusters_db[msg.process.pm_id])
      return console.error('Unknown id %s', msg.process.pm_id);

    util._extend(God.clusters_db[msg.process.pm_id].pm2_env.axm_monitor, Utility.clone(msg.data));
    msg = null;
  });

  /**
   * Broadcast messages
   */
  God.bus.onAny(function(event, data_v) {
    if (['axm:action',
         'axm:monitor',
         'axm:option:setPID',
         'axm:option:configuration'].indexOf(event) > -1) {
      data_v = null;
      return false;
    }
    that.pub.emit(event, Utility.clone(data_v));
    data_v = null;
  });
}
```
- example usage
```shell
...
  sendSignalToProcessName : God.sendSignalToProcessName,

  ping                    : God.ping,
  getVersion              : God.getVersion,
  reloadLogs              : God.reloadLogs
});

this.startLogic();
}

Daemon.prototype.close = function(opts, cb) {
var that = this;

God.bus.emit('pm2:kill', {
  status : 'killed',
...
```



# <a name="apidoc.module.pm2.God"></a>[module pm2.God](#apidoc.module.pm2.God)

#### <a name="apidoc.element.pm2.God.checkProcess"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>checkProcess (pid)](#apidoc.element.pm2.God.checkProcess)
- description and source-code
```javascript
checkProcess = function (pid) {
  if (!pid) return false;

  try {
    // Sending 0 signal do not kill the process
    process.kill(pid, 0);
    return true;
  }
  catch (err) {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.deleteProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>deleteProcessId (id, cb)](#apidoc.element.pm2.God.deleteProcessId)
- description and source-code
```javascript
deleteProcessId = function (id, cb) {
  God.stopProcessId(id, function(err, proc) {
    if (err) return cb(God.logAndGenerateError(err), {});
    // ! transform to slow object
    delete God.clusters_db[id];

    if (Object.keys(God.clusters_db).length == 0)
      God.next_id = 0;
    return cb(null, proc);
  });
  return false;
}
```
- example usage
```shell
...

  God.dumpProcessList(function() {

var processes = God.getFormatedProcesses();

async.eachLimit(processes, 1, function(proc, next) {
  console.log('Deleting process %s', proc.pm2_env.pm_id);
  God.deleteProcessId(proc.pm2_env.pm_id, function() {
    return next();
  });
  return false;
}, function(err) {
  try {
    fs.unlinkSync(that.pid_path);
  } catch(e) {}
...
```

#### <a name="apidoc.element.pm2.God.dumpProcessList"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>dumpProcessList (cb)](#apidoc.element.pm2.God.dumpProcessList)
- description and source-code
```javascript
dumpProcessList = function (cb) {
  var process_list = [];
  var apps         = Utility.clone(God.getFormatedProcesses());

  // Don't override the actual dump file if process list is empty
  // unless user explicitely did 'pm2 dump'.
  // This often happens when PM2 crashed, we don't want to override
  // the dump file with an empty list of process.
  if (!apps[0]) {
    debug('[PM2] Did not override dump file because list of processes is empty');
    return cb(null, {success:true, process_list: process_list});
  }

  function fin(err) {
    try {
      fs.writeFileSync(cst.DUMP_FILE_PATH, JSON.stringify(process_list));
    } catch (e) {
      console.error(e.stack || e);
    }
    return cb(null, {success:true, process_list: process_list});
  }

  function saveProc(apps) {
    if (!apps[0])
      return fin(null);
    delete apps[0].pm2_env.instances;
    delete apps[0].pm2_env.pm_id;
    // Do not dump modules
    if (!apps[0].pm2_env.pmx_module)
      process_list.push(apps[0].pm2_env);
    apps.shift();
    return saveProc(apps);
  }
  saveProc(apps);
}
```
- example usage
```shell
...
}

Daemon.prototype.gracefullExit = function() {
  var that = this;

  console.log('pm2 has been killed by signal, dumping process list before exit...');

  God.dumpProcessList(function() {

var processes = God.getFormatedProcesses();

async.eachLimit(processes, 1, function(proc, next) {
  console.log('Deleting process %s', proc.pm2_env.pm_id);
  God.deleteProcessId(proc.pm2_env.pm_id, function() {
    return next();
...
```

#### <a name="apidoc.element.pm2.God.duplicateProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>duplicateProcessId (id, cb)](#apidoc.element.pm2.God.duplicateProcessId)
- description and source-code
```javascript
duplicateProcessId = function (id, cb) {
  if (!(id in God.clusters_db))
    return cb(God.logAndGenerateError(id + ' id unknown'), {});

  if (!God.clusters_db[id] || !God.clusters_db[id].pm2_env)
    return cb(God.logAndGenerateError('Error when getting proc || proc.pm2_env'), {});

  var proc = Utility.clone(God.clusters_db[id].pm2_env);

  delete proc.created_at;
  delete proc.pm_id;

  God.executeApp(proc, function(err, clu) {
    God.notify('start', clu, true);
    cb(err, [Utility.clone(clu)]);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.executeApp"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>executeApp (env, cb)](#apidoc.element.pm2.God.executeApp)
- description and source-code
```javascript
function executeApp(env, cb) {
  var env_copy = Utility.clone(env);

  Utility.extend(env_copy, env_copy.env);

  env_copy['status']         = cst.LAUNCHING_STATUS;
  env_copy['pm_uptime']      = Date.now();
  env_copy['axm_actions']    = [];
  env_copy['axm_monitor']    = {};
  env_copy['axm_options']    = {};
  env_copy['axm_dynamic']    = {};
  env_copy['vizion_running'] =
    env_copy['vizion_running'] !== undefined ? env_copy['vizion_running'] : false;

  if (!env_copy.created_at)
    env_copy['created_at'] = Date.now();

<span class="apidocCodeCommentSpan">  /**
   * Enter here when it's the first time that the process is created
   * 1 - Assign a new id
   * 2 - Reset restart time and unstable_restarts
   * 3 - Assign a log file name depending on the id
   * 4 - If watch option is set, look for changes
   */
</span>  if (env_copy['pm_id'] === undefined) {
    env_copy['pm_id']             = God.getNewId();
    env_copy['restart_time']      = 0;
    env_copy['unstable_restarts'] = 0;

    // add -pm_id to pid file
    env_copy.pm_pid_path = env_copy.pm_pid_path.replace(/-[0-9]+\.pid$|\.pid$/g, '-' + env_copy['pm_id'] + '.pid');

    // If merge option, dont separate the logs
    if (!env_copy['merge_logs']) {
      ['', '_out', '_err'].forEach(function(k){
        var key = 'pm' + k + '_log_path';
        env_copy[key] && (env_copy[key] = env_copy[key].replace(/-[0-9]+\.log$|\.log$/g, '-' + env_copy['pm_id'] + '.log'));
      });
    }

    // Initiate watch file
    if (env_copy['watch']) {
      God.watch.enable(env_copy);
    }
  }

  /**
   * Avoid 'Resource leak error' due to 'disconnect' event
   * not being fired sometimes
   */
  var workAround = function(worker) {
    var listeners = null;

    listeners = worker.process.listeners('exit')[0];
    var exit = listeners[Object.keys(listeners)[0]];

    listeners = worker.process.listeners('disconnect')[0];
    var disconnect = listeners[Object.keys(listeners)[0]];

    worker.process.removeListener('exit', exit);
    worker.process.once('exit', function(exitCode, signalCode) {
      // If disconnect() has not been called
      // earlier, we call it here.
      if (worker.state != 'disconnected')
        disconnect();
      // Call the original 'exit' callback
      exit(exitCode, signalCode);
    });
  };

  /** Callback when application is launched */
  var readyCb = function ready(proc) {
      if (proc.pm2_env.vizion !== false && proc.pm2_env.vizion !== "false")
        God.finalizeProcedure(proc);
      else
        God.notify('online', proc);

      proc.pm2_env.status = cst.ONLINE_STATUS;
      console.log('App name:%s id:%s online', proc.pm2_env.name, proc.pm2_env.pm_id);
      if (cb) cb(null, proc);
  }

  if (env_copy.exec_mode === 'cluster_mode') {
    /**
     * Cluster mode logic (for NodeJS apps)
     */
    God.nodeApp(env_copy, function nodeApp(err, clu) {
      if (cb && err) return cb(err);
      if (err) return false;

      var old_env = God.clusters_db[clu.pm2_env.pm_id];

      if (old_env) {
        old_env = null;
        God.clusters_db[clu.pm2_env.pm_id] = null;
      }

      God.clusters_db[clu.pm2_env.pm_id] = clu;

      if (semver.lt(process.version, '7.0.0') === true) {
        // Temporary
        workAround(clu);
      }

      clu.once('error', function(err) {
        console.error(err.stack || err);
        clu.pm2_env.status = cst.ERRORED_STATUS;
        try {
          clu.destroy && clu.destroy();
        }
        catch (e) {
          console.error(e.stack || e);
          God.handleExit(clu, cst.ERROR_EXIT);
        }
      });

      clu.once('disconnect', function() {
        console.log('App name:%s id:%s disconnected', clu.pm2_env.name, clu.pm2_env.pm_id);
      });

      clu.once('exit', function cluExit(code, signal) {
        God.handleExit(clu, code || 0, signal || 'SIGINT');
      });

      return clu.once('online', function () {
        return readyCb(clu);
      });
    });
  }
  else {
    /**
     * Fork mode logic
     */
    God.forkMode(env_copy, function forkMode(err, clu) {
      if (cb && err) return cb(err);
      if (err) return false; ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.finalizeProcedure"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>finalizeProcedure (proc)](#apidoc.element.pm2.God.finalizeProcedure)
- description and source-code
```javascript
function finalizeProcedure(proc) {
  var last_path    = '';
  var current_path = proc.pm2_env.cwd || path.dirname(proc.pm2_env.pm_exec_path);
  var proc_id      = proc.pm2_env.pm_id;

  if (proc.pm2_env.vizion_running === true) {
    debug('Vizion is already running for proc id: %d, skipping this round', proc_id);
    return God.notify('online', proc);
  }

  proc.pm2_env.vizion_running = true;
  vizion.analyze({folder : current_path}, function recur_path(err, meta){
    var proc = God.clusters_db[proc_id];

    if (err)
      debug(err.stack || err);

    if (!proc ||
        !proc.pm2_env ||
        proc.pm2_env.status == cst.STOPPED_STATUS ||
        proc.pm2_env.status == cst.STOPPING_STATUS) {
      return console.error('Proc is not defined anymore or is being killed');
    }

    proc.pm2_env.vizion_running = false;

    if (!err) {
      proc.pm2_env.versioning = meta;
      proc.pm2_env.versioning.repo_path = current_path;
      God.notify('online', proc);
    }
    else if (err && current_path === last_path) {
      proc.pm2_env.versioning = null;
      God.notify('online', proc);
    }
    else {
      last_path = current_path;
      current_path = path.dirname(current_path);
      proc.pm2_env.vizion_running = true;
      vizion.analyze({folder : current_path}, recur_path);
    }
    return false;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.findByName"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>findByName (name)](#apidoc.element.pm2.God.findByName)
- description and source-code
```javascript
findByName = function (name) {
  var db = God.clusters_db;
  var arr = [];

  if (name == 'all') {
    for (var key in db) {
      // Avoid _old_proc process style
      if (typeof(God.clusters_db[key].pm2_env.pm_id) === 'number')
        arr.push(db[key]);
    }
    return arr;
  }

  for (var key in db) {
    if (God.clusters_db[key].pm2_env.name == name ||
        God.clusters_db[key].pm2_env.pm_exec_path == p.resolve(name)) {
      arr.push(db[key]);
    }
  }
  return arr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.findProcessById"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>findProcessById (id)](#apidoc.element.pm2.God.findProcessById)
- description and source-code
```javascript
function findProcessById(id) {
  return God.clusters_db[id] ? God.clusters_db[id] : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.forceGc"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>forceGc (opts, cb)](#apidoc.element.pm2.God.forceGc)
- description and source-code
```javascript
forceGc = function (opts, cb) {
  if (global.gc) {
    global.gc();
    debug('Garbage collection triggered successfully');
    if (cb) cb(null, {success: true});
  }
  else {
    debug('Garbage collection failed');
    if (cb) cb(null, {success: false});
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.forkMode"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>forkMode (pm2_env, cb)](#apidoc.element.pm2.God.forkMode)
- description and source-code
```javascript
function forkMode(pm2_env, cb) {
  var command = '';
  var args    = [];

  console.log('Starting execution sequence in -fork mode- for app name:%s id:%s',
              pm2_env.name,
              pm2_env.pm_id);
  var spawn = require('child_process').spawn;

  var interpreter = pm2_env.exec_interpreter || 'node';
  var pidFile     = pm2_env.pm_pid_path;

  if (interpreter !== 'none') {
    command = interpreter;

    if (pm2_env.node_args && Array.isArray(pm2_env.node_args)) {
      args = args.concat(pm2_env.node_args);
    }

    // Deprecated - to remove at some point
    if (process.env.PM2_NODE_OPTIONS) {
      args = args.concat(process.env.PM2_NODE_OPTIONS.split(' '));
    }

    if (interpreter === 'node' || RegExp('node$').test(interpreter)) {
      args.push(path.resolve(path.dirname(module.filename), '..', 'ProcessContainerFork.js'));
    }
    else
      args.push(pm2_env.pm_exec_path);
  }
  else {
    command = pm2_env.pm_exec_path;
    args = [ ];
  }

  if (pm2_env.args) {
    args = args.concat(pm2_env.args);
  }

  // piping stream o file
  var stds = {
    out: pm2_env.pm_out_log_path,
    err: pm2_env.pm_err_log_path
  };

  // entire log std if necessary.
  if ('pm_log_path' in pm2_env){
    stds.std = pm2_env.pm_log_path;
  }

  log("stds: %j", stds);

  Utility.startLogging(stds, function(err, result) {
    if (err) {
      God.logAndGenerateError(err);
      return cb(err);
    };

    try {
      var cspr = spawn(command, args, {
        env      : pm2_env,
        detached : true,
        cwd      : pm2_env.pm_cwd || process.cwd(),
        stdio    : ['pipe', 'pipe', 'pipe', 'ipc'] //Same as fork() in node core
      });
    } catch(e) {
      God.logAndGenerateError(e);
      return cb(e);
    }

    cspr.process = {};
    cspr.process.pid = cspr.pid;
    cspr.pm2_env = pm2_env;

    cspr.stderr.on('data', function forkErrData(data) {
      var log_data = null;

      if (pm2_env.log_type && pm2_env.log_type === 'json') {
        log_data = JSON.stringify({
          message : data.toString(),
        timestamp : pm2_env.log_date_format ? moment().format(pm2_env.log_date_format) : new Date().toISOString(),
          type : 'err',
          process_id : cspr.pm2_env.pm_id,
          app_name : cspr.pm2_env.name
        }) + '\n';
      }
      else if (pm2_env.log_date_format)
        log_data = moment().format(pm2_env.log_date_format) + ': ' + data.toString();
      else
        log_data = data.toString();

      stds.std && stds.std.write && stds.std.write(log_data);

      // hardcoded values of special log path to not write on disk
      if (pm2_env.pm_err_log_path !== 'NULL' && pm2_env.pm_err_log_path !== '/dev/null') {
        stds.err.write && stds.err.write(log_data);
      }

      God.bus.emit('log:err', {
        process : {
          pm_id      : cspr.pm2_env.pm_id,
          name       : cspr.pm2_env.name,
          rev        : (cspr.pm2_env.versioning && cspr.pm2_env.versioning.revision) ? cspr.pm2_env.versioning.revision : null
        },
        at  : Utility.getDate(),
        data : log_data
      });
    });

    cspr.stdout.on('data', function forkOutData(data) {
      var log_data = null;

      if (pm2_env.log_type && pm2_env.log_type === 'json') {
        log_data = JSON.stringify({
          message : data.toString(),
          timestamp : pm2_env.log_date_format ? moment().format(pm2_env.log_date_format) : new Date().toISOString(),
          type : 'out',
          process_id : cspr.pm2_env.pm_id,
          app_name : cspr.pm2_env.name
        }) + '\n';
      }
      else if (pm2_env.log_date_format)
        log_data = moment().format(pm2_env.log_date_format) + ': ' + data.toString();
      else
        log_data = data.toString();

      stds.std && stds.std.write && stds.std.write(log_data);

      // hardcoded values of special log path to not write on disk
      if (pm2_env.pm_out_log_path !== 'NULL' && pm2_env.pm_out_log_path !== '/dev/null') {
        stds.out.write && stds.out.write(log_data);
      }

      God.bus.emit('log:out', {
        process : { ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.getFormatedProcess"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>getFormatedProcess (id)](#apidoc.element.pm2.God.getFormatedProcess)
- description and source-code
```javascript
function getFormatedProcesses(id) {
  if (God.clusters_db[id])
    return {
      pid     : God.clusters_db[id].process.pid,
      name    : God.clusters_db[id].pm2_env.name,
      pm2_env : God.clusters_db[id].pm2_env,
      pm_id   : God.clusters_db[id].pm2_env.pm_id
    };
  return {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.getFormatedProcesses"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>getFormatedProcesses ()](#apidoc.element.pm2.God.getFormatedProcesses)
- description and source-code
```javascript
function getFormatedProcesses() {
  var keys = Object.keys(God.clusters_db);
  var arr  = new Array();
  var kl   = keys.length;

  for (var i = 0; i < kl; i++) {
    var key = keys[i];

    if (!God.clusters_db[key]) continue;
    // Avoid _old type pm_ids
    if (isNaN(God.clusters_db[key].pm2_env.pm_id)) continue;

    arr.push({
      pid     : God.clusters_db[key].process.pid,
      name    : God.clusters_db[key].pm2_env.name,
      pm2_env : God.clusters_db[key].pm2_env,
      pm_id   : God.clusters_db[key].pm2_env.pm_id
    })
  }
  return arr;
}
```
- example usage
```shell
...
Daemon.prototype.gracefullExit = function() {
  var that = this;

  console.log('pm2 has been killed by signal, dumping process list before exit...');

  God.dumpProcessList(function() {

var processes = God.getFormatedProcesses();

async.eachLimit(processes, 1, function(proc, next) {
  console.log('Deleting process %s', proc.pm2_env.pm_id);
  God.deleteProcessId(proc.pm2_env.pm_id, function() {
    return next();
  });
  return false;
...
```

#### <a name="apidoc.element.pm2.God.getMonitorData"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>getMonitorData (env, cb)](#apidoc.element.pm2.God.getMonitorData)
- description and source-code
```javascript
function getMonitorData(env, cb) {
  var processes = God.getFormatedProcesses();

  async.eachSeries(processes, function computeMonitor(pro, next) {
    if (pro.pm2_env.status == cst.ONLINE_STATUS) {
      var pid = pro.pid;

      if (pro.pm2_env.axm_options && pro.pm2_env.axm_options.pid) {
        if (isNaN(pro.pm2_env.axm_options.pid)) {
          pro['monit'] = {
            memory : 0,
            cpu : 0
          };
          return process.nextTick(next);
        }
        pid = pro.pm2_env.axm_options.pid;
      }

      pidusage.stat(pid, function retPidUsage(err, res) {
        if (err) {
          // Do not log, some time modules does not retrieve PID
          // console.error('Error caught while calling pidusage');
          // console.error(err);
          pro['monit'] = {
            memory : 0,
            cpu : 0
          };
          return next();
        }

        pro['monit'] = {
          memory : Math.floor(res.memory),
          cpu    : Math.floor(res.cpu)
        };
        res = null;
        pid = null;
        return next();
      });
    }
    else {
      pro['monit'] = {
        memory : 0,
        cpu : 0
      };
      return next();
    }
  }, function retMonitor(err, res) {
    if (err) return cb(God.logAndGenerateError(err), null);
    return cb(null, processes);
  });

}
```
- example usage
```shell
...
  var tasks = function() {
    if (God.Worker.is_running === true) {
debug('[PM2][WORKER] Worker is already running, skipping this round');
return false;
    }
    God.Worker.is_running = true;

    God.getMonitorData(null, function(err, data) {
if (err || !data || typeof(data) !== 'object') {
  God.Worker.is_running = false;
  return console.error(err);
}

async.eachLimit(data, 1, function(proc_key, next) {
  if (!proc_key ||
...
```

#### <a name="apidoc.element.pm2.God.getNewId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>getNewId ()](#apidoc.element.pm2.God.getNewId)
- description and source-code
```javascript
getNewId = function () {
  return God.next_id++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.getProcesses"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>getProcesses ()](#apidoc.element.pm2.God.getProcesses)
- description and source-code
```javascript
getProcesses = function () {
  return God.clusters_db;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.getSystemData"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>getSystemData (env, cb)](#apidoc.element.pm2.God.getSystemData)
- description and source-code
```javascript
function getSystemData(env, cb) {
  God.getMonitorData(env, function(err, processes) {
    cb(err, {
      system: {
        hostname: os.hostname(),
        uptime: os.uptime(),
        cpus: os.cpus(),
        load: os.loadavg(),
        memory: {
          free: os.freemem(),
          total: os.totalmem()
        },
        time: Utility.getDate()
      },
      processes: processes
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.getVersion"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>getVersion (env, cb)](#apidoc.element.pm2.God.getVersion)
- description and source-code
```javascript
getVersion = function (env, cb) {
  process.nextTick(function() {
    return cb(null, pkg.version);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.handleExit"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>handleExit (clu, exit_code, kill_signal)](#apidoc.element.pm2.God.handleExit)
- description and source-code
```javascript
function handleExit(clu, exit_code, kill_signal) {
  console.log('App [%s] with id [%s] and pid [%s], exited with code [%s] via signal [%s]', clu.pm2_env.name, clu.pm2_env.pm_id,
clu.process.pid, exit_code, kill_signal || 'SIGINT');

  var proc = this.clusters_db[clu.pm2_env.pm_id];

  if (!proc) {
    console.error('Process undefined ? with process id ', clu.pm2_env.pm_id);
    return false;
  }

  if (proc.process.pid)
    pidusage.unmonitor(proc.process.pid);

  var stopping    = (proc.pm2_env.status == cst.STOPPING_STATUS
                     || proc.pm2_env.status == cst.STOPPED_STATUS
                     || proc.pm2_env.status == cst.ERRORED_STATUS) || (proc.pm2_env.autorestart === false ||
                                                                       proc.pm2_env.autorestart === "false");

  var overlimit   = false;

  if (stopping) proc.process.pid = 0;

  // Reset probes and actions
  if (proc.pm2_env.axm_actions) proc.pm2_env.axm_actions = [];
  if (proc.pm2_env.axm_monitor) proc.pm2_env.axm_monitor = {};

  if (proc.pm2_env.status != cst.ERRORED_STATUS &&
      proc.pm2_env.status != cst.STOPPING_STATUS)
    proc.pm2_env.status = cst.STOPPED_STATUS;

  if (proc.pm2_env.pm_id.toString().indexOf('_old_') !== 0) {
    try {
      fs.unlinkSync(proc.pm2_env.pm_pid_path);
    } catch (e) {
      debug('Error when unlinking pid file', e);
    }
  }

<span class="apidocCodeCommentSpan">  /**
   * Avoid infinite reloop if an error is present
   */
</span>  // If the process has been created less than 15seconds ago

  // And if the process has an uptime less than a second
  var min_uptime = typeof(proc.pm2_env.min_uptime) !== 'undefined' ? proc.pm2_env.min_uptime : 1000;
  var max_restarts = typeof(proc.pm2_env.max_restarts) !== 'undefined' ? proc.pm2_env.max_restarts : 16;

  if ((Date.now() - proc.pm2_env.created_at) < (min_uptime * max_restarts)) {
    if ((Date.now() - proc.pm2_env.pm_uptime) < min_uptime) {
      // Increment unstable restart
      proc.pm2_env.unstable_restarts += 1;
    }

    if (proc.pm2_env.unstable_restarts >= max_restarts) {
      // Too many unstable restart in less than 15 seconds
      // Set the process as 'ERRORED'
      // And stop restarting it
      proc.pm2_env.status = cst.ERRORED_STATUS;
      proc.process.pid = 0;

      console.log('Script %s had too many unstable restarts (%d). Stopped. %j',
                  proc.pm2_env.pm_exec_path,
                  proc.pm2_env.unstable_restarts,
                  proc.pm2_env.status);

      God.notify('restart overlimit', proc);

      proc.pm2_env.unstable_restarts = 0;
      proc.pm2_env.created_at = null;
      overlimit = true;
    }
  }

  if (typeof(exit_code) !== 'undefined') proc.pm2_env.exit_code = exit_code;

  God.notify('exit', proc);

  if (God.pm2_being_killed) {
    console.log('[HandleExit] PM2 is being killed, stopping restart procedure...');
    return false;
  }

  var restart_delay = 0;
  if (proc.pm2_env.restart_delay !== undefined && !isNaN(parseInt(proc.pm2_env.restart_delay))) {
    restart_delay = parseInt(proc.pm2_env.restart_delay);
  }

  if (!stopping && !overlimit) {
    //make this property unenumerable
    Object.defineProperty(proc.pm2_env, 'restart_task', {configurable: true, writable: true});
    proc.pm2_env.restart_task = setTimeout(function() {
      proc.pm2_env.restart_time += 1;
      God.executeApp(proc.pm2_env);
    }, restart_delay);
  }

  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.killProcess"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>killProcess (pid, pm2_env, cb)](#apidoc.element.pm2.God.killProcess)
- description and source-code
```javascript
killProcess = function (pid, pm2_env, cb) {
  if (!pid) return cb({msg : 'no pid passed or null'});

  var mode = pm2_env.exec_mode;

  if (pm2_env.treekill !== true) {
    try {
      process.kill(parseInt(pid), 'SIGINT');
    } catch(e) {
      console.error('[SimpleKill] %s pid can not be killed', pid, e.stack, e.message);
    }
    return God.processIsDead(pid, pm2_env, cb);
  }
  else {
    treekill(parseInt(pid), 'SIGINT', function(err) {
      return God.processIsDead(pid, pm2_env, cb);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.logAndGenerateError"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>logAndGenerateError (err)](#apidoc.element.pm2.God.logAndGenerateError)
- description and source-code
```javascript
logAndGenerateError = function (err) {
  // Is an Error object
  if (err instanceof Error) {
    console.trace(err);
    return err;
  }
  // Is a JSON or simple string
  console.error(err);
  return new Error(err);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.msgProcess"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>msgProcess (cmd, cb)](#apidoc.element.pm2.God.msgProcess)
- description and source-code
```javascript
msgProcess = function (cmd, cb) {
  if ('id' in cmd) {
    var id = cmd.id;
    if (!(id in God.clusters_db))
      return cb(God.logAndGenerateError(id + ' id unknown'), {});
    var proc = God.clusters_db[id];

    var action_exist = false;

    proc.pm2_env.axm_actions.forEach(function(action) {
      if (action.action_name == cmd.msg) {
        action_exist = true;
        // Reset output buffer
        action.output = [];
      }
    });
    if (action_exist == false) {
      return cb(God.logAndGenerateError('Action doesn\'t exist ' + cmd.msg + ' for ' + proc.pm2_env.name), {});
    }

    if (proc.pm2_env.status == cst.ONLINE_STATUS || proc.pm2_env.status == cst.LAUNCHING_STATUS) {
<span class="apidocCodeCommentSpan">      /*
       * Send message
       */
</span>      if (cmd.opts == null)
        proc.send(cmd.msg);
      else
        proc.send(cmd);

      return cb(null, { process_count : 1, success : true });
    }
    else
      return cb(God.logAndGenerateError(id + ' : id offline'), {});
  }

  else if ('name' in cmd) {
    /*
     * As names are not unique in case of cluster, this
     * will send msg to all process matching  'name'
     */
    var name = cmd.name;
    var arr = Object.keys(God.clusters_db);
    var sent = 0;

    (function ex(arr) {
      if (arr[0] == null) return cb(null, { process_count : sent, success : true });

      var id      = arr[0];
      var proc_env = God.clusters_db[id].pm2_env;

      if (p.basename(proc_env.pm_exec_path) == name || proc_env.name == name) {
        if (proc_env.status == cst.ONLINE_STATUS || proc.pm2_env.status == cst.LAUNCHING_STATUS) {

          if (cmd.opts == null)
            God.clusters_db[id].send(cmd.msg);
          else
            God.clusters_db[id].send(cmd);

          sent++;
          arr.shift();
          return ex(arr);

        }
      }
      else {
        arr.shift();
        return ex(arr);
      }
      return false;
    })(arr);
  }

  else return cb(God.logAndGenerateError('method requires name or id field'), {});
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.nodeApp"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>nodeApp (env_copy, cb)](#apidoc.element.pm2.God.nodeApp)
- description and source-code
```javascript
function nodeApp(env_copy, cb){
  var clu = null;

  console.log('Starting execution sequence in -cluster mode- for app name:%s id:%s',
              env_copy.name,
              env_copy.pm_id);

  if (env_copy.node_args && Array.isArray(env_copy.node_args)) {
    cluster.settings.execArgv = env_copy.node_args;
  }

  env_copy._pm2_version = pkg.version;

  try {
    // node.js cluster clients can not receive deep-level objects or arrays in the forked process, e.g.:
    // { "args": ["foo", "bar"], "env": { "foo1": "bar1" }} will be parsed to
    // { "args": "foo, bar", "env": "[object Object]"}
    // So we passing a stringified JSON here.
    clu = cluster.fork({pm2_env: JSON.stringify(env_copy)});
  } catch(e) {
    God.logAndGenerateError(e);
    return cb(e);
  }

  clu.pm2_env = env_copy;

<span class="apidocCodeCommentSpan">  /**
   * Broadcast message to God
   */
</span>  clu.on('message', function cluMessage(msg) {
    /*********************************
     * If you edit this function
     * Do the same in ForkMode.js !
     *********************************/
    if (msg.data && msg.type) {
      return God.bus.emit(msg.type ? msg.type : 'process:msg', {
        at      : Utility.getDate(),
        data    : msg.data,
        process :  {
          pm_id      : clu.pm2_env.pm_id,
          name       : clu.pm2_env.name,
          rev        : (clu.pm2_env.versioning && clu.pm2_env.versioning.revision) ? clu.pm2_env.versioning.revision : null
        }
      });
    }
    else {

      if (typeof msg == 'object' && 'node_version' in msg) {
        clu.pm2_env.node_version = msg.node_version;
        return false;
      } else if (typeof msg == 'object' && 'cron_restart' in msg) {
        return God.restartProcessId({
          id : clu.pm2_env.pm_id
        }, function() {
          console.log('Application %s has been restarted via CRON', clu.pm2_env.name);
        });
      }

      return God.bus.emit('process:msg', {
        at      : Utility.getDate(),
        raw     : msg,
        process :  {
          pm_id      : clu.pm2_env.pm_id,
          name       : clu.pm2_env.name
        }
      });
    }
  });

  return cb(null, clu);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.notify"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>notify (action_name, data, manually)](#apidoc.element.pm2.God.notify)
- description and source-code
```javascript
notify = function (action_name, data, manually) {
  God.bus.emit('process:event', {
    event      : action_name,
    manually   : typeof(manually) == 'undefined' ? false : true,
    process    : Utility.formatCLU(data),
    at         : Utility.getDate()
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.notifyByProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>notifyByProcessId (opts, cb)](#apidoc.element.pm2.God.notifyByProcessId)
- description and source-code
```javascript
notifyByProcessId = function (opts, cb) {
  if (typeof(opts.id) === 'undefined') { return cb(new Error('process id missing')); }
  var proc = God.clusters_db[opts.id];
  if (!proc) { return cb(new Error('process id doesnt exists')); }

  God.bus.emit('process:event', {
    event      : opts.action_name,
    manually   : typeof(opts.manually) == 'undefined' ? false : true,
    process    : Utility.formatCLU(proc),
    at         : Utility.getDate()
  });

  process.nextTick(function() {
    return cb ? cb(null) : false;
  });
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.notifyKillPM2"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>notifyKillPM2 ()](#apidoc.element.pm2.God.notifyKillPM2)
- description and source-code
```javascript
notifyKillPM2 = function () {
  God.pm2_being_killed = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.ping"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>ping (env, cb)](#apidoc.element.pm2.God.ping)
- description and source-code
```javascript
ping = function (env, cb) {
  return cb(null, {msg : 'pong'});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.prepare"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>prepare (env, cb)](#apidoc.element.pm2.God.prepare)
- description and source-code
```javascript
function prepare(env, cb) {
  // If instances option is set (-i [arg])
  if (typeof env.instances != 'undefined') {
    if (env.instances == 0) env.instances = numCPUs;
    env.instances = parseInt(env.instances);
    if (env.instances < 0) env.instances += numCPUs;
    if (env.instances <= 0) env.instances = 1;
    // multi fork depending on number of cpus
    var arr = [];
    var instance_id = 0;

    (function ex(i) {
      if (i <= 0) {
        if (cb) return cb(null, arr);
        return false;
      }

      env.NODE_APP_INSTANCE = instance_id++;
      env.vizion_running = false;

      if (env.env && env.env.vizion_running)
        env.env.vizion_running = false;

      return God.executeApp(Utility.clone(env), function(err, clu) {
        if (err) return ex(i - 1);
        arr.push(Utility.clone(clu));
        God.notify('start', clu, true);
        return ex(i - 1);
      });
    })(env.instances);
  }
  else {
    env.vizion_running = false;
    if (env.env && env.env.vizion_running) env.env.vizion_running = false;

    return God.executeApp(env, function(err, clu) {
      God.notify('start', clu, true);
      cb(err, [Utility.clone(clu)]);
    });
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.processIsDead"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>processIsDead (pid, pm2_env, cb, sigkill)](#apidoc.element.pm2.God.processIsDead)
- description and source-code
```javascript
processIsDead = function (pid, pm2_env, cb, sigkill) {
  if (!pid) return cb({type : 'param:missing', msg : 'no pid passed'});

  var timeout      = null;
  var kill_timeout = (pm2_env && pm2_env.kill_timeout) ? pm2_env.kill_timeout : cst.KILL_TIMEOUT;
  var mode         = pm2_env.exec_mode;

  var timer = setInterval(function() {
    if (God.checkProcess(pid) === false) {
      console.log('pid=%d msg=process killed', pid);
      clearTimeout(timeout);
      clearInterval(timer);
      return cb(null, true);
    }
    console.log('pid=%d msg=failed to kill - retrying in 100ms', pid);
    return false;
  }, 100);

  timeout = setTimeout(function() {
    clearInterval(timer);
    if (sigkill) {
      console.log('Process with pid %d could not be killed', pid);
      return cb({type : 'timeout', msg : 'timeout'});
    }
    else {
      console.log('Process with pid %d still alive after %sms, sending it SIGKILL now...', pid, kill_timeout);

      if (pm2_env.treekill !== true) {
        try {
          process.kill(parseInt(pid), 'SIGKILL');
        } catch(e) {
          console.error('[SimpleKill][SIGKILL] %s pid can not be killed', pid, e.stack, e.message);
        }
        return God.processIsDead(pid, pm2_env, cb, true);
      }
      else {
        treekill(parseInt(pid), 'SIGKILL', function(err) {
          return God.processIsDead(pid, pm2_env, cb, true);
        });
      }
    }
  }, kill_timeout);
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.reloadLogs"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>reloadLogs (opts, cb)](#apidoc.element.pm2.God.reloadLogs)
- description and source-code
```javascript
reloadLogs = function (opts, cb) {
  console.log('Reloading logs...');
  var processIds = Object.keys(God.clusters_db);

  processIds.forEach(function (id) {
    var cluster = God.clusters_db[id];

    console.log('Reloading logs for process id %d', id);

    if (cluster &&
        cluster.pm2_env) {
      if (cluster.send &&
          cluster.pm2_env.exec_mode == 'cluster_mode') {
        cluster.send({
          type:'log:reload'
        });
      }
      else if (cluster._reloadLogs) {
        cluster._reloadLogs(function(err) {
          if (err) God.logAndGenerateError(err);
        });
      }
    }
  });

  return cb(null, {});
}
```
- example usage
```shell
...
var that = this;

process.on('SIGTERM', that.gracefullExit);
process.on('SIGINT', that.gracefullExit);
process.on('SIGHUP', function() {});
process.on('SIGQUIT', that.gracefullExit);
process.on('SIGUSR2', function() {
  God.reloadLogs({}, function() {});
});
}

Daemon.prototype.sendReady = function(cb) {
// Send ready message to Client
if (this.rpc_socket_ready == true && this.pub_socket_ready == true) {
  cb(null, {
...
```

#### <a name="apidoc.element.pm2.God.reloadProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>reloadProcessId (opts, cb)](#apidoc.element.pm2.God.reloadProcessId)
- description and source-code
```javascript
reloadProcessId = function (opts, cb) {
  var id  = opts.id;
  var env = opts.env || {};

  if (!(id in God.clusters_db))
    return cb(new Error('PM2 ID unknown'));

  if (God.clusters_db[id].pm2_env.status == cst.ONLINE_STATUS &&
      God.clusters_db[id].pm2_env.exec_mode == 'cluster_mode') {

    Utility.extendExtraConfig(God.clusters_db[id], opts);
    Utility.extend(God.clusters_db[id].pm2_env.env, opts.env);

    var wait_msg = God.clusters_db[id].pm2_env.wait_ready ? 'ready' : 'listening';
    return hardReload(God, id, wait_msg, cb);
  }
  else {
    console.log('Process %s in a stopped status, starting it', id);
    return God.restartProcessId(opts, cb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.resetMetaProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>resetMetaProcessId (id, cb)](#apidoc.element.pm2.God.resetMetaProcessId)
- description and source-code
```javascript
resetMetaProcessId = function (id, cb) {
  if (!(id in God.clusters_db))
    return cb(God.logAndGenerateError(id + ' id unknown'), {});

  if (!God.clusters_db[id] || !God.clusters_db[id].pm2_env)
    return cb(God.logAndGenerateError('Error when getting proc || proc.pm2_env'), {});

  God.clusters_db[id].pm2_env.created_at = Utility.getDate();
  God.clusters_db[id].pm2_env.unstable_restarts = 0;
  God.clusters_db[id].pm2_env.restart_time = 0;

  return cb(null, God.getFormatedProcesses());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.resetState"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>resetState (pm2_env)](#apidoc.element.pm2.God.resetState)
- description and source-code
```javascript
resetState = function (pm2_env) {
  pm2_env.created_at = Date.now();
  pm2_env.unstable_restarts = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.restartProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>restartProcessId (opts, cb)](#apidoc.element.pm2.God.restartProcessId)
- description and source-code
```javascript
restartProcessId = function (opts, cb) {
  var id = opts.id;
  var env = opts.env || {};

  if (typeof(id) === 'undefined')
    return cb(God.logAndGenerateError('opts.id not passed to restartProcessId', opts));
  if (!(id in God.clusters_db))
    return cb(God.logAndGenerateError('God db process id unknown'), {});

  var proc = God.clusters_db[id];

  God.resetState(proc.pm2_env);

<span class="apidocCodeCommentSpan">  /**
   * Merge new application configuration on restart
   * Same system in reloadProcessId and softReloadProcessId
   */
</span>  Utility.extendExtraConfig(proc, opts);
  Utility.extend(proc.pm2_env.env, opts.env);

  if (God.pm2_being_killed) {
    return cb(God.logAndGenerateError('[RestartProcessId] PM2 is being killed, stopping restart procedure...'));
  }
  if (proc.pm2_env.status === cst.ONLINE_STATUS || proc.pm2_env.status === cst.LAUNCHING_STATUS) {
    God.stopProcessId(id, function(err) {
      if (God.pm2_being_killed)
        return cb(God.logAndGenerateError('[RestartProcessId] PM2 is being killed, stopping restart procedure...'));
      proc.pm2_env.restart_time += 1;
      return God.startProcessId(id, cb);
    });

    return false;
  }
  else {
    debug('[restart] process not online, starting it');
    return God.startProcessId(id, cb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.restartProcessName"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>restartProcessName (name, cb)](#apidoc.element.pm2.God.restartProcessName)
- description and source-code
```javascript
restartProcessName = function (name, cb) {
  var processes = God.findByName(name);

  if (processes && processes.length === 0)
    return cb(God.logAndGenerateError('Unknown process'), {});

  async.eachLimit(processes, cst.CONCURRENT_ACTIONS, function(proc, next) {
    if (God.pm2_being_killed)
      return next('[Watch] PM2 is being killed, stopping restart procedure...');
    if (proc.pm2_env.status === cst.ONLINE_STATUS)
      return God.restartProcessId({id:proc.pm2_env.pm_id}, next);
    else if (proc.pm2_env.status !== cst.STOPPING_STATUS
             && proc.pm2_env.status !== cst.LAUNCHING_STATUS)
      return God.startProcessId(proc.pm2_env.pm_id, next);
    else
      return next("[Watch] Process name %s is being stopped so I won't restart it", name);
  }, function(err) {
    if (err) return cb(God.logAndGenerateError(err));
    return cb(null, God.getFormatedProcesses());
  });

  return false;
}
```
- example usage
```shell
...
return false;
      }

      self.restarting = true;

      console.error('Change detected on path %s for app %s - restarting', path, pm2_env.name);

      God.restartProcessName(pm2_env.name, function(err, list) {
self.restarting = false;

if (err) {
  log('Error while restarting', err);
  return false;
}
...
```

#### <a name="apidoc.element.pm2.God.sendDataToProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>sendDataToProcessId (packet, cb)](#apidoc.element.pm2.God.sendDataToProcessId)
- description and source-code
```javascript
sendDataToProcessId = function (packet, cb) {
  if (typeof(packet.id) == undefined ||
      !packet.data ||
      !packet.topic)
    return cb(God.logAndGenerateError('ID, DATA or TOPIC field is missing'), {});

  var pm_id = packet.id;
  var data  = packet.data;

  var proc = God.clusters_db[pm_id];

  if (!proc)
    return cb(God.logAndGenerateError('Process with ID ', pm_id, ' unknown!'), {});

  if (proc.pm2_env.status != cst.ONLINE_STATUS && proc.pm2_env.status != cst.LAUNCHING_STATUS)
    return cb(God.logAndGenerateError('Process with ID ', pm_id, ' unknown!'), {});

  try {
    proc.send(packet);
  }
  catch(e) {
    return cb(God.logAndGenerateError(e), {});
  }

  return cb(null, {
    success: true,
    data   : packet
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.sendSignalToProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>sendSignalToProcessId (opts, cb)](#apidoc.element.pm2.God.sendSignalToProcessId)
- description and source-code
```javascript
sendSignalToProcessId = function (opts, cb) {
  var id = opts.process_id;
  var signal = opts.signal;

  if (!(id in God.clusters_db))
    return cb(God.logAndGenerateError(id + ' id unknown'), {});

  var proc = God.clusters_db[id];

  //God.notify('send signal ' + signal, proc, true);

  try {
    process.kill(God.clusters_db[id].process.pid, signal);
  } catch(e) {
    return cb(God.logAndGenerateError('Error when sending signal (signal unknown)'), {});
  }
  return cb(null, God.getFormatedProcesses());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.sendSignalToProcessName"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>sendSignalToProcessName (opts, cb)](#apidoc.element.pm2.God.sendSignalToProcessName)
- description and source-code
```javascript
sendSignalToProcessName = function (opts, cb) {
  var processes = God.findByName(opts.process_name);
  var signal    = opts.signal;

  if (processes && processes.length === 0)
    return cb(God.logAndGenerateError('Unknown process name'), {});

  async.eachLimit(processes, cst.CONCURRENT_ACTIONS, function(proc, next) {
    if (proc.pm2_env.status == cst.ONLINE_STATUS || proc.pm2_env.status == cst.LAUNCHING_STATUS) {
      try {
        process.kill(proc.process.pid, signal);
      } catch(e) {
        return next(e);
      }
    }
    return setTimeout(next, 200);
  }, function(err) {
    if (err) return cb(God.logAndGenerateError(err), {});
    return cb(null, God.getFormatedProcesses());
  });

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.softReloadProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>softReloadProcessId (opts, cb)](#apidoc.element.pm2.God.softReloadProcessId)
- description and source-code
```javascript
softReloadProcessId = function (opts, cb) {
  var id  = opts.id;
  var env = opts.env || {};

  if (!(id in God.clusters_db))
    return cb(new Error('PM ID unknown'));

  if (God.clusters_db[id].pm2_env.status == cst.ONLINE_STATUS &&
      God.clusters_db[id].pm2_env.exec_mode == 'cluster_mode' &&
      !God.clusters_db[id].pm2_env.wait_ready) {

    Utility.extendExtraConfig(God.clusters_db[id], opts);
    Utility.extend(God.clusters_db[id].pm2_env.env, opts.env);

    return softReload(God, id, cb);
  }
  else {
    console.log('Process %s in a stopped status, starting it', id);
    return God.restartProcessId(opts, cb);
  }
}
```
- example usage
```shell
...

if (proc_key.monit.memory !== undefined &&
    proc.pm2_env.max_memory_restart !== undefined &&
    proc.pm2_env.max_memory_restart < proc_key.monit.memory &&
    proc.pm2_env.axm_options &&
    proc.pm2_env.axm_options.pid === undefined) {
  console.log('[PM2][WORKER] Process %s restarted because it exceeds --max-memory-restart value (current_memory=%s max_memory_limit
=%s [octets])', proc.pm2_env.pm_id, proc_key.monit.memory, proc.pm2_env.max_memory_restart);
  God.softReloadProcessId({
    id : proc.pm2_env.pm_id
  }, function(err, data) {
    if (err)
      console.error(err.stack || err);
    return cb();
  });
}
...
```

#### <a name="apidoc.element.pm2.God.startProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>startProcessId (id, cb)](#apidoc.element.pm2.God.startProcessId)
- description and source-code
```javascript
startProcessId = function (id, cb) {
  if (!(id in God.clusters_db))
    return cb(God.logAndGenerateError(id + ' id unknown'), {});

  var proc = God.clusters_db[id];
  if (proc.pm2_env.status == cst.ONLINE_STATUS)
    return cb(God.logAndGenerateError('process already online'), {});
  if (proc.pm2_env.status == cst.LAUNCHING_STATUS)
    return cb(God.logAndGenerateError('process already started'), {});
  if (proc.process && proc.process.pid)
    return cb(God.logAndGenerateError('Process with pid ' + proc.process.pid + ' already exists'), {});

  return God.executeApp(God.clusters_db[id].pm2_env, function(err, proc) {
    return cb(err, Utility.clone(proc));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.startWatch"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>startWatch (method, value, fn)](#apidoc.element.pm2.God.startWatch)
- description and source-code
```javascript
startWatch = function (method, value, fn) {
  var env = null;

  if (method == 'restartProcessId') {
    env = God.clusters_db[value.id];
  } else if(method == 'restartProcessName') {
    env = God.clusters_db[God.findByName(value)];
  }

  if (env) {
    if (env.pm2_env.watch)
      return fn(null, {success:true, notrestarted:true});

    God.watch.enable(env.pm2_env);
    //env.pm2_env.env.watch = true;
    env.pm2_env.watch = true;
  }

  return fn(null, {success:true});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.stopProcessId"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>stopProcessId (id, cb)](#apidoc.element.pm2.God.stopProcessId)
- description and source-code
```javascript
stopProcessId = function (id, cb) {
  if (typeof id == 'object' && 'id' in id)
    id = id.id;

  if (!(id in God.clusters_db))
    return cb(God.logAndGenerateError(id + ' : id unknown'), {});

  //clear time-out restart task
  clearTimeout(God.clusters_db[id].pm2_env.restart_task);

  if (God.clusters_db[id].pm2_env.status == cst.STOPPED_STATUS)
    return cb(null, God.getFormatedProcess(id));
  // state == 'none' means that the process is not online yet
  if (God.clusters_db[id].state && God.clusters_db[id].state === 'none')
    return setTimeout(function() { God.stopProcessId(id, cb); }, 250);

  var proc     = God.clusters_db[id];

  console.log('Stopping app:%s id:%s', proc.pm2_env.name, proc.pm2_env.pm_id);
  proc.pm2_env.status = cst.STOPPING_STATUS;

  if (!proc.process.pid) {
    console.error('app=%s id=%d does not have a pid', proc.pm2_env.name, proc.pm2_env.pm_id);
    proc.pm2_env.status = cst.STOPPED_STATUS;
    return cb(null, { error : true, message : 'could not kill process w/o pid'});
  }

  God.killProcess(proc.process.pid, proc.pm2_env, function(err) {
    proc.pm2_env.status = cst.STOPPED_STATUS;
    pidusage.unmonitor(proc.process.pid);

    God.notify('exit', proc);

    if (err && err.type && err.type === 'timeout') {
      console.error('app=%s id=%d pid=%s could not be stopped',
                    proc.pm2_env.name,
                    proc.pm2_env.pm_id,
                    proc.process.pid);
      proc.pm2_env.status = cst.ERRORED_STATUS;
      return cb(null, God.getFormatedProcess(id));
    }

    if (proc.pm2_env.pm_id.toString().indexOf('_old_') !== 0) {
      try {
        fs.unlinkSync(proc.pm2_env.pm_pid_path);
      } catch (e) {}
    }

    if (proc.pm2_env.axm_actions) proc.pm2_env.axm_actions = [];
    if (proc.pm2_env.axm_monitor) proc.pm2_env.axm_monitor = {};

    proc.process.pid = 0;
    return cb(null, God.getFormatedProcess(id));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.God.stopWatch"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>stopWatch (method, value, fn)](#apidoc.element.pm2.God.stopWatch)
- description and source-code
```javascript
stopWatch = function (method, value, fn) {
  var env = null;

  if (method == 'stopAll' || method == 'deleteAll') {
    var processes = God.getFormatedProcesses();

    processes.forEach(function(proc) {
      God.clusters_db[proc.pm_id].pm2_env.watch = false;
      God.watch.disable(proc.pm2_env);
    });

  } else {

    if (method.indexOf('ProcessId') !== -1) {
      env = God.clusters_db[value];
    } else if (method.indexOf('ProcessName') !== -1) {
      env = God.clusters_db[God.findByName(value)];
    }

    if (env) {
      God.watch.disable(env.pm2_env);
      env.pm2_env.watch = false;
    }
  }
  return fn(null, {success:true});
}
```
- example usage
```shell
...
 * @return
 */
Client.prototype.executeRemote = function executeRemote(method, app_conf, fn) {
var self = this;

// stop watch on stop | env is the process id
if (method.indexOf('stop') !== -1) {
  this.stopWatch(method, app_conf);
}
// stop watching when process is deleted
else if (method.indexOf('delete') !== -1) {
  this.stopWatch(method, app_conf);
}
// stop everything on kill
else if (method.indexOf('kill') !== -1) {
...
```

#### <a name="apidoc.element.pm2.God.toggleWatch"></a>[function <span class="apidocSignatureSpan">pm2.God.</span>toggleWatch (method, value, fn)](#apidoc.element.pm2.God.toggleWatch)
- description and source-code
```javascript
toggleWatch = function (method, value, fn) {
  var env = null;

  if (method == 'restartProcessId') {
    env = God.clusters_db[value.id];
  } else if(method == 'restartProcessName') {
    env = God.clusters_db[God.findByName(value)];
  }

  if (env) {
    //env.pm2_env.env.watch = !env.pm2_env.env.watch;
    env.pm2_env.watch = !env.pm2_env.watch;
    if (env.pm2_env.watch)
      God.watch.enable(env.pm2_env);
    else
      God.watch.disable(env.pm2_env);
  }

  return fn(null, {success:true});
}
```
- example usage
```shell
...
}
// stop everything on kill
else if (method.indexOf('kill') !== -1) {
  this.stopWatch('deleteAll', app_conf);
}
else if (method.indexOf('restartProcessId') !== -1 && process.argv.indexOf('--watch') > -1) {
  delete app_conf.env.current_conf.watch;
  this.toggleWatch(method, app_conf);
}

if (!this.client || !this.client.call) {
  this.start(function(error) {
    if (error) {
      if (fn)
        return fn(error);
...
```



# <a name="apidoc.module.pm2.Satan"></a>[module pm2.Satan](#apidoc.module.pm2.Satan)

#### <a name="apidoc.element.pm2.Satan.disconnectBus"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>disconnectBus (cb)](#apidoc.element.pm2.Satan.disconnectBus)
- description and source-code
```javascript
function disconnectBus(cb) {
  this.sub_sock.once('close', function() {
    return cb ? cb() : false;
  });
  this.sub_sock.close();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Satan.disconnectRPC"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>disconnectRPC (cb)](#apidoc.element.pm2.Satan.disconnectRPC)
- description and source-code
```javascript
function disconnectRPC(cb) {
  debug('Disconnecting PM2 RPC');

  if (!Satan.client_sock || !Satan.client_sock.close) {
    return cb({
      success : false,
      msg : 'RPC connection to PM2 is not launched'
    });
  }

  if (Satan.client_sock.connected == false ||
      Satan.client_sock.closing == true) {
    return cb({
      success : false,
      msg : 'RPC closed'
    });
  }

  try {
    var timer;

    Satan.client_sock.once('close', function() {
      clearTimeout(timer);
      debug('PM2 RPC cleanly closed');
      return cb ? cb(null, {success:true}) : false;
    });

    timer = setTimeout(function() {
      if (Satan.client_sock.destroy)
        Satan.client_sock.destroy();
      return cb ? cb(null, {success:true}) : false;
    }, 200);

    Satan.client_sock.close();
  } catch(e) {
    debug('Error while disconnecting RPC PM2', e.stack || e);
    return cb ? cb(e.stack || e) : false;
  };
  return false;
}
```
- example usage
```shell
...
 * @param {} fn
 * @return
 */
Satan.killDaemon = function killDaemon(fn) {
var timeout;

function quit() {
  Satan.disconnectRPC(function() {
    debug('RPC disconnected');
    return fn ? fn(null, {success:true}) : false;
  });
}

process.once('SIGQUIT', function() {
  debug('Received SIGQUIT');
...
```

#### <a name="apidoc.element.pm2.Satan.executeRemote"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>executeRemote (method, env, fn)](#apidoc.element.pm2.Satan.executeRemote)
- description and source-code
```javascript
function executeRemote(method, env, fn) {
  var env_watch = false;

  if (env.env && env.env.watch)
    env_watch = env.env.watch;

  env_watch = util.isArray(env_watch) && env_watch.length === 0 ? !!~process.argv.indexOf('--watch') : env_watch;

  //stop watching when process is deleted
  if (method.indexOf('delete') !== -1) {
    Satan.stopWatch(method, env);
  //stop everything on kill
  } else if(method.indexOf('kill') !== -1) {
    Satan.stopWatch('deleteAll', env);
  //stop watch on stop (stop doesn't accept env, yet)
  } else if (~process.argv.indexOf('--watch') && method.indexOf('stop') !== -1) {
    Satan.stopWatch(method, env);
  //restart watch
  } else if (env_watch && method.indexOf('restart') !== -1) {
    Satan.restartWatch(method, env);
  }

  if (!Satan.client || !Satan.client.call) {
    if (fn) return fn(new Error('Could not connect to local pm2, have you called pm2.connect(function()})'));
    console.error('Did you forgot to call pm2.connect(function() { }) before interacting with PM2 ?');
    return process.exit(0);
  }

  debug('Calling daemon method pm2:%s', method);
  return Satan.client.call(method, env, fn);
}
```
- example usage
```shell
...
}

debug('Calling daemon method pm2:%s on rpc socket:%s', method, this.rpc_socket_file);
return this.client.call(method, app_conf, fn);
};

Client.prototype.notifyGod = function(action_name, id, cb) {
this.executeRemote('notifyByProcessId', {
  id : id,
  action_name : action_name,
  manually : true
}, function() {
  debug('God notified');
  return cb ? cb() : false;
});
...
```

#### <a name="apidoc.element.pm2.Satan.getExposedMethods"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>getExposedMethods (cb)](#apidoc.element.pm2.Satan.getExposedMethods)
- description and source-code
```javascript
function getExposedMethods(cb) {
  Satan.client.methods(cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Satan.killDaemon"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>killDaemon (fn)](#apidoc.element.pm2.Satan.killDaemon)
- description and source-code
```javascript
function killDaemon(fn) {
  var timeout;

  function quit() {
    Satan.disconnectRPC(function() {
      debug('RPC disconnected');
      return fn ? fn(null, {success:true}) : false;
    });
  }

  process.once('SIGQUIT', function() {
    debug('Received SIGQUIT');
    clearTimeout(timeout);
    quit();
  });

  timeout = setTimeout(function() {
    quit();
  }, 3000);

  // Kill daemon
  Satan.executeRemote('killMe', {pid : process.pid}, function() {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Satan.launchBus"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>launchBus (cb)](#apidoc.element.pm2.Satan.launchBus)
- description and source-code
```javascript
function launchEventSystem(cb) {
  var self = this;
  this.sub = axon.socket('sub-emitter');
  this.sub_sock = this.sub.connect(cst.DAEMON_PUB_PORT);

  this.sub_sock.once('connect', function() {
    return cb(null, self.sub);
  });
}
```
- example usage
```shell
...
fmt.field('Watch and Restart', chalk.green('Enabled'));
fmt.field('Ignored folder', opts.ignore_watch || 'node_modules');
if (opts.postExec)
  fmt.field('Post restart cmd', opts.postExec);
fmt.sep();

setTimeout(function() {
  pm2.Client.launchBus(function(err, bus) {
    bus.on('process:event', function(packet) {
      if (packet.event == 'online') {
        if (opts.postExec)
          postExecCmd(opts.postExec);
      }
    });
  });
...
```

#### <a name="apidoc.element.pm2.Satan.launchDaemon"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>launchDaemon (cb)](#apidoc.element.pm2.Satan.launchDaemon)
- description and source-code
```javascript
function launchDaemon(cb) {
  debug('Launching daemon');

  var SatanJS = p.resolve(p.dirname(module.filename), 'Satan.js');
  var InteractorDaemonizer = require('./Interactor/InteractorDaemonizer.js');

  var node_args = [];

  var out, err;

  if (process.env.TRAVIS) {
    // Redirect PM2 internal err and out to STDERR STDOUT when running with Travis
    out = 1;
    err = 2;
  }
  else {
    out = fs.openSync(cst.PM2_LOG_FILE_PATH, 'a'),
    err = fs.openSync(cst.PM2_LOG_FILE_PATH, 'a');
  }

  // Node.js tuning for better performance
  //node_args.push('--expose-gc'); // Allows manual GC in the code
  //node_args.push('--gc-global'); // Does full GC (smaller memory footprint)

<span class="apidocCodeCommentSpan">  /**
   * Add node [arguments] depending on PM2_NODE_OPTIONS env variable
   */
</span>  if (process.env.PM2_NODE_OPTIONS)
    node_args = node_args.concat(process.env.PM2_NODE_OPTIONS.split(' '));
  node_args.push(SatanJS);

  var resolved_home = process.env.PM2_HOME || process.env.HOME || process.env.HOMEPATH;

  debug("PM2 home path: %s", resolved_home);
  debug("Node.js engine full path: %s", process.execPath);
  debug("Node.js with V8 arguments: %s", node_args);

  var child = require('child_process').spawn(process.execPath || 'node', node_args, {
    detached   : true,
    cwd        : process.cwd(),
    env        : util._extend({
      'SILENT' : cst.DEBUG ? !cst.DEBUG : true,
      'HOME'   : resolved_home
    }, process.env),
    stdio      : ['ipc', out, err]
  });

  function onError(e) {
    console.error(e.stack || e);
    return cb ? cb(e.stack || e) : false;
  }

  child.once('error', onError);

  child.unref();

  child.once('message', function(msg) {
    debug('PM2 daemon launched with return message: ', msg);
    child.removeListener('error', onError);
    child.disconnect();
    InteractorDaemonizer.launchAndInteract({}, function(err, data) {
      if (data)
        debug('Interactor launched');
      return cb ? cb(null, child) : false;
    });
  });
}
```
- example usage
```shell
...
  });
  return false;
}

/**
 * Daemon mode
 */
that.launchDaemon(function(err, child) {
  if (err) {
    Common.printError(err);
    return cb ? cb(err) : process.exit(that.conf.ERROR_EXIT);
  }
  Common.printOut(that.conf.PREFIX_MSG + 'PM2 Successfully daemonized');
  that.launchRPC(function(err, meta) {
    return cb(null, {
...
```

#### <a name="apidoc.element.pm2.Satan.launchRPC"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>launchRPC (cb)](#apidoc.element.pm2.Satan.launchRPC)
- description and source-code
```javascript
function launchRPC(cb) {
  debug('Launching RPC client on socket file %s', cst.DAEMON_RPC_PORT);
  var req      = axon.socket('req');
  Satan.client = new rpc.Client(req);

  Satan.client.sock.once('connect', function() {
    debug('Connected to Daemon');
    process.emit('satan:client:ready');
    setTimeout(function() {
      return cb ? cb(null) : false;
    }, 4);
  });

  this.client_sock = req.connect(cst.DAEMON_RPC_PORT);
}
```
- example usage
```shell
...
// @breaking change (noDaemonMode has been drop)
// @todo ret err
Client.prototype.start = function(cb) {
var that = this;

this.pingDaemon(function(daemonAlive) {
  if (daemonAlive == true)
    return that.launchRPC(function(err, meta) {
      return cb(null, {
        daemon_mode      : that.conf.daemon_mode,
        new_pm2_instance : false,
        rpc_socket_file  : that.rpc_socket_file,
        pub_socket_file  : that.pub_socket_file,
        pm2_home         : that.pm2_home
      });
...
```

#### <a name="apidoc.element.pm2.Satan.notifyGod"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>notifyGod (action_name, id, cb)](#apidoc.element.pm2.Satan.notifyGod)
- description and source-code
```javascript
notifyGod = function (action_name, id, cb) {
  Satan.executeRemote('notifyByProcessId', {
    id : id,
    action_name : action_name,
    manually : true
  }, function() {
    debug('God notified');
    return cb ? cb() : false;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Satan.pingDaemon"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>pingDaemon (cb)](#apidoc.element.pm2.Satan.pingDaemon)
- description and source-code
```javascript
function pingDaemon(cb) {
  var req    = axon.socket('req');
  var client = new rpc.Client(req);

  debug('[PING PM2] Trying to connect to server');

  client.sock.once('reconnect attempt', function() {
    client.sock.close();
    debug('Daemon not launched');
    process.nextTick(function() {
      return cb(false);
    });
  });

  client.sock.once('connect', function() {
    client.sock.once('close', function() {
      return cb(true);
    });
    client.sock.close();
    debug('Daemon alive');
  });

  req.connect(cst.DAEMON_RPC_PORT);
}
```
- example usage
```shell
...
}

// @breaking change (noDaemonMode has been drop)
// @todo ret err
Client.prototype.start = function(cb) {
var that = this;

this.pingDaemon(function(daemonAlive) {
  if (daemonAlive == true)
    return that.launchRPC(function(err, meta) {
      return cb(null, {
        daemon_mode      : that.conf.daemon_mode,
        new_pm2_instance : false,
        rpc_socket_file  : that.rpc_socket_file,
        pub_socket_file  : that.pub_socket_file,
...
```

#### <a name="apidoc.element.pm2.Satan.printOut"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>printOut ()](#apidoc.element.pm2.Satan.printOut)
- description and source-code
```javascript
printOut = function () {
  if (process.env.PM2_SILENT || process.env.PM2_PROGRAMMATIC === 'true') return false;
  return console.log.apply(console, arguments);
}
```
- example usage
```shell
...
 * Daemon mode
 */
that.launchDaemon(function(err, child) {
  if (err) {
    Common.printError(err);
    return cb ? cb(err) : process.exit(that.conf.ERROR_EXIT);
  }
  Common.printOut(that.conf.PREFIX_MSG + 'PM2 Successfully daemonized');
  that.launchRPC(function(err, meta) {
    return cb(null, {
      daemon_mode      : that.conf.daemon_mode,
      new_pm2_instance : true,
      rpc_socket_file  : that.rpc_socket_file,
      pub_socket_file  : that.pub_socket_file,
      pm2_home         : that.pm2_home
...
```

#### <a name="apidoc.element.pm2.Satan.processStateHandler"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>processStateHandler (God)](#apidoc.element.pm2.Satan.processStateHandler)
- description and source-code
```javascript
processStateHandler = function (God) {
<span class="apidocCodeCommentSpan">  /**
   * Description
   * @method gracefullExit
   * @return
   */
</span>  function gracefullExit() {
    Satan.printOut('pm2 has been killed by signal, dumping process list before exit...');

    God.dumpProcessList(function() {

      var processes = God.getFormatedProcesses();

      async.eachLimit(processes, cst.CONCURRENT_ACTIONS, function(proc, next) {
        console.log('Deleting process %s', proc.pm2_env.pm_id);
        God.deleteProcessId(proc.pm2_env.pm_id, function() {
          return next();
        });
        return false;
      }, function(err) {
        try {
          fs.unlinkSync(cst.PM2_PID_FILE_PATH);
        } catch(e) {}
        Satan.printOut('[PM2] Exited peacefully');
        process.exit(cst.SUCCESS_EXIT);
      });
    });
  }

  try {
    fs.writeFileSync(cst.PM2_PID_FILE_PATH, process.pid);
  } catch (e) {
    console.error(e.stack || e);
  }

  process.on('SIGILL', function() {
    global.gc();
    Satan.printOut('Running garbage collector');
  });

  process.on('SIGTERM', gracefullExit);
  process.on('SIGINT', gracefullExit);
  process.on('SIGQUIT', gracefullExit);
  process.on('SIGUSR2', function() {
    God.reloadLogs({}, function() {});
  });
}
```
- example usage
```shell
...
var God = require('./God');
var self = this;

var pkg    = require('../package.json');
var rpc_socket_ready = false;
var pub_socket_ready = false;

Satan.processStateHandler(God);

function sendReady() {
  // Send ready message to Satan Client
  if (rpc_socket_ready == true && pub_socket_ready == true) {
    if (typeof(process.send) === 'function') {
      process.send({
        online      : true,
...
```

#### <a name="apidoc.element.pm2.Satan.remoteWrapper"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>remoteWrapper ()](#apidoc.element.pm2.Satan.remoteWrapper)
- description and source-code
```javascript
remoteWrapper = function () {
  // Only require here because God init himself
  var God = require('./God');
  var self = this;

  var pkg    = require('../package.json');
  var rpc_socket_ready = false;
  var pub_socket_ready = false;

  Satan.processStateHandler(God);

  function sendReady() {
    // Send ready message to Satan Client
    if (rpc_socket_ready == true && pub_socket_ready == true) {
      if (typeof(process.send) === 'function') {
        process.send({
          online      : true,
          success     : true,
          pid         : process.pid,
          pm2_version : pkg.version
        });
      }
    };
  }

<span class="apidocCodeCommentSpan">  /**
   * External interaction part
   */
</span>
  /**
   * Pub system for real time notifications
   */
  var pub    = axon.socket('pub-emitter');

  this.pub_socket = pub.bind(cst.DAEMON_PUB_PORT);

  this.pub_socket.once('bind', function() {
    Satan.printOut('BUS system [READY] on port %s', cst.DAEMON_PUB_PORT);
    pub_socket_ready = true;
    sendReady();
  });

  /**
   * Rep/Req - RPC system to interact with God
   */
  var rep    = axon.socket('rep');

  var server = new rpc.Server(rep);

  Satan.printOut('[[[[ PM2/God daemon launched ]]]]');

  this.rpc_socket = rep.bind(cst.DAEMON_RPC_PORT);

  this.rpc_socket.once('bind', function() {
    Satan.printOut('RPC interface [READY] on port %s', cst.DAEMON_RPC_PORT);
    rpc_socket_ready = true;
    sendReady();
  });

  server.expose({
    prepare                 : God.prepare,
    getMonitorData          : God.getMonitorData,
    getSystemData           : God.getSystemData,

    startProcessId          : God.startProcessId,
    stopProcessId           : God.stopProcessId,
    restartProcessId        : God.restartProcessId,
    deleteProcessId         : God.deleteProcessId,

    softReloadProcessId     : God.softReloadProcessId,
    reloadProcessId         : God.reloadProcessId,
    duplicateProcessId      : God.duplicateProcessId,
    resetMetaProcessId      : God.resetMetaProcessId,
    stopWatch               : God.stopWatch,
    restartWatch            : God.restartWatch,
    notifyByProcessId       : God.notifyByProcessId,

    killMe                  : God.killMe,
    notifyKillPM2           : God.notifyKillPM2,
    forceGc                 : God.forceGc,

    findByFullPath          : God.findByFullPath,

    msgProcess              : God.msgProcess,
    sendDataToProcessId     : God.sendDataToProcessId,
    sendSignalToProcessId   : God.sendSignalToProcessId,
    sendSignalToProcessName : God.sendSignalToProcessName,

    ping                    : God.ping,
    getVersion              : God.getVersion,
    reloadLogs              : God.reloadLogs
  });

  /**
   * Action treatment specifics
   * Attach actions to pm2_env.axm_actions variables (name + options)
   */
  God.bus.on('axm:action', function axmActions(msg) {
    var pm2_env = msg.process;
    var exists  = false;
    var axm_action = msg.data;

    if (!pm2_env || !God.clusters_db[pm2_env.pm_id])
      return console.error('Unknown id %s', pm2_env.pm_id);

    if (!God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions)
      God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions = [];

    God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions.forEach(function(actions) {
      if (actions.action_name == axm_action.action_name)
        exists = true;
    });

    if (exists === false) {
      debug('Adding action', axm_action);
      God.clusters_db[pm2_env.pm_id].pm2_env.axm_actions.push(axm_action);
    }

    return God;
  });

  /**
   * Configure module
   */
  God.bus.on('axm:option:configuration', function axmMonitor(msg) {
    if (!msg.process)
      return console.error('[axm:option:configuration] no process defined');

    if (!God.clusters_db[msg.process.pm_id])
      return console.error('[axm:option:configuration] Unknown id %s', msg.process.pm_id);

    try {
      // Application Name nverride
      if (msg.data.name)
        God.clusters_db[msg.process.pm_id].pm2_env.name = msg.data.name;

      Object.keys(msg.data).forEach(function(conf_key) {
        God.clusters_db[msg.process.pm_id]. ...
```
- example usage
```shell
...
  Satan._noDaemonMode = noDaemonMode;

  Satan.pingDaemon(function(ab) {
    // If Daemon not alive
    if (ab == false) {
if (noDaemonMode) {
  debug('Launching in no daemon mode');
  Satan.remoteWrapper();
  return Satan.launchRPC(function() {
    require('./Modularizer.js').launchAll(cb);
  });
}

Satan.printOut(cst.PREFIX_MSG + 'Spawning PM2 daemon');
...
```

#### <a name="apidoc.element.pm2.Satan.restartWatch"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>restartWatch (method, env, fn)](#apidoc.element.pm2.Satan.restartWatch)
- description and source-code
```javascript
function restartWatch(method, env, fn) {
  debug('Calling restartWatch');
  Satan.client.call('restartWatch', method, env, function() {
    debug('Restart watching');
    return fn ? fn() : false;
  });
}
```
- example usage
```shell
...
} else if(method.indexOf('kill') !== -1) {
  Satan.stopWatch('deleteAll', env);
//stop watch on stop (stop doesn't accept env, yet)
} else if (~process.argv.indexOf('--watch') && method.indexOf('stop') !== -1) {
  Satan.stopWatch(method, env);
//restart watch
} else if (env_watch && method.indexOf('restart') !== -1) {
  Satan.restartWatch(method, env);
}

if (!Satan.client || !Satan.client.call) {
  if (fn) return fn(new Error('Could not connect to local pm2, have you called pm2.connect(function()})'));
  console.error('Did you forgot to call pm2.connect(function() { }) before interacting with PM2 ?');
  return process.exit(0);
}
...
```

#### <a name="apidoc.element.pm2.Satan.start"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>start (noDaemonMode, cb)](#apidoc.element.pm2.Satan.start)
- description and source-code
```javascript
start = function (noDaemonMode, cb) {
  if (typeof(noDaemonMode)  == "function") {
    cb = noDaemonMode;
    noDaemonMode = false;
  }

  Satan._noDaemonMode = noDaemonMode;

  Satan.pingDaemon(function(ab) {
    // If Daemon not alive
    if (ab == false) {
      if (noDaemonMode) {
        debug('Launching in no daemon mode');
        Satan.remoteWrapper();
        return Satan.launchRPC(function() {
          require('./Modularizer.js').launchAll(cb);
        });
      }

      Satan.printOut(cst.PREFIX_MSG + 'Spawning PM2 daemon');

      // Daemonize PM2
      return Satan.launchDaemon(function(err, child) {
        if (err) {
          console.error(err);
          return cb ? cb(err) : process.exit(cst.ERROR_EXIT);
        }
        Satan.printOut(cst.PREFIX_MSG + 'PM2 Successfully daemonized');
        // Launch RPC
        return Satan.launchRPC(function() {
          require('./Modularizer.js').launchAll(cb);
        });
      });
    }
    // Else just start the PM2 client side (RPC)
    return Satan.launchRPC(cb);
  });
}
```
- example usage
```shell
...
}
else if (method.indexOf('restartProcessId') !== -1 && process.argv.indexOf('--watch') > -1) {
  delete app_conf.env.current_conf.watch;
  this.toggleWatch(method, app_conf);
}

if (!this.client || !this.client.call) {
  this.start(function(error) {
    if (error) {
      if (fn)
        return fn(error);
      console.error(error);
      return process.exit(0);
    }
    return self.client.call(method, app_conf, fn);
...
```

#### <a name="apidoc.element.pm2.Satan.stopWatch"></a>[function <span class="apidocSignatureSpan">pm2.Satan.</span>stopWatch (method, env, fn)](#apidoc.element.pm2.Satan.stopWatch)
- description and source-code
```javascript
function stopWatch(method, env, fn) {
  debug('Calling stopWatch');
  Satan.client.call('stopWatch', method, env, function() {
    debug('Stop watching');
    return fn ? fn() : false;
  });
}
```
- example usage
```shell
...
 * @return
 */
Client.prototype.executeRemote = function executeRemote(method, app_conf, fn) {
var self = this;

// stop watch on stop | env is the process id
if (method.indexOf('stop') !== -1) {
  this.stopWatch(method, app_conf);
}
// stop watching when process is deleted
else if (method.indexOf('delete') !== -1) {
  this.stopWatch(method, app_conf);
}
// stop everything on kill
else if (method.indexOf('kill') !== -1) {
...
```



# <a name="apidoc.module.pm2.Utility"></a>[module pm2.Utility](#apidoc.module.pm2.Utility)

#### <a name="apidoc.element.pm2.Utility.clone"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>clone (obj)](#apidoc.element.pm2.Utility.clone)
- description and source-code
```javascript
clone = function (obj) {
  if (obj === null || obj === undefined) return {};
  return fclone(obj);
}
```
- example usage
```shell
...

  try {
    // Application Name nverride
    if (msg.data.name)
      God.clusters_db[msg.process.pm_id].pm2_env.name = msg.data.name;

    Object.keys(msg.data).forEach(function(conf_key) {
      God.clusters_db[msg.process.pm_id].pm2_env.axm_options[conf_key] = Utility.clone(msg.data[conf_key]);
    });
  } catch(e) {
    console.error(e.stack || e);
  }
  msg = null;
});
...
```

#### <a name="apidoc.element.pm2.Utility.extend"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>extend (destination, source)](#apidoc.element.pm2.Utility.extend)
- description and source-code
```javascript
extend = function (destination, source){
  if (!source || typeof source != 'object') return destination;

    Object.keys(source).forEach(function(new_key) {
      if (source[new_key] != '[object Object]')
        destination[new_key] = source[new_key];
    });

  return destination;
}
```
- example usage
```shell
...

var Utility = module.exports = {
getDate : function() {
  return Date.now();
},
extendExtraConfig : function(proc, opts) {
  if (opts.env && opts.env.current_conf) {
    Utility.extend(proc.pm2_env, opts.env.current_conf);
    delete opts.env.current_conf;
  }
},
formatCLU : function(process) {
  if (!process.pm2_env) {
    return process;
  }
...
```

#### <a name="apidoc.element.pm2.Utility.extendExtraConfig"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>extendExtraConfig (proc, opts)](#apidoc.element.pm2.Utility.extendExtraConfig)
- description and source-code
```javascript
extendExtraConfig = function (proc, opts) {
  if (opts.env && opts.env.current_conf) {
    Utility.extend(proc.pm2_env, opts.env.current_conf);
    delete opts.env.current_conf;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Utility.formatCLU"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>formatCLU (process)](#apidoc.element.pm2.Utility.formatCLU)
- description and source-code
```javascript
formatCLU = function (process) {
  if (!process.pm2_env) {
    return process;
  }

  var obj = Utility.clone(process.pm2_env);
  delete obj.env;

  return obj;
}
```
- example usage
```shell
...

module.exports = function(God) {

God.notify = function(action_name, data, manually) {
  God.bus.emit('process:event', {
    event      : action_name,
    manually   : typeof(manually) == 'undefined' ? false : true,
    process    : Utility.formatCLU(data),
    at         : Utility.getDate()
  });
};

God.notifyByProcessId = function(opts, cb) {
  if (typeof(opts.id) === 'undefined') { return cb(new Error('process id missing')); }
  var proc = God.clusters_db[opts.id];
...
```

#### <a name="apidoc.element.pm2.Utility.getDate"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>getDate ()](#apidoc.element.pm2.Utility.getDate)
- description and source-code
```javascript
getDate = function () {
  return Date.now();
}
```
- example usage
```shell
...
module.exports = function(God) {

God.notify = function(action_name, data, manually) {
  God.bus.emit('process:event', {
    event      : action_name,
    manually   : typeof(manually) == 'undefined' ? false : true,
    process    : Utility.formatCLU(data),
    at         : Utility.getDate()
  });
};

God.notifyByProcessId = function(opts, cb) {
  if (typeof(opts.id) === 'undefined') { return cb(new Error('process id missing')); }
  var proc = God.clusters_db[opts.id];
  if (!proc) { return cb(new Error('process id doesnt exists')); }
...
```

#### <a name="apidoc.element.pm2.Utility.overrideConsole"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>overrideConsole (bus)](#apidoc.element.pm2.Utility.overrideConsole)
- description and source-code
```javascript
overrideConsole = function (bus) {
  if (cst.PM2_LOG_DATE_FORMAT && typeof cst.PM2_LOG_DATE_FORMAT == 'string'){
    var moment = require('moment');

    // Generate timestamp prefix
    function timestamp(){
      return moment().format(cst.PM2_LOG_DATE_FORMAT) + ': ';
    }

    var hacks = ['info', 'log', 'error', 'warn'], consoled = {};

    // store console functions.
    hacks.forEach(function(method){
      consoled[method] = console[method];
    });

    hacks.forEach(function(k){
      console[k] = function(){
        if (bus) {
          bus.emit('log:PM2', {
            process : {
              pm_id      : 'PM2',
              name       : 'PM2',
              rev        : null
            },
            at  : Utility.getDate(),
            data : util.format.apply(this, arguments) + '\n'
          });
        }
        // do not destroy variable insertion
        arguments[0] && (arguments[0] = timestamp() + arguments[0]);
        consoled[k].apply(console, arguments);
      };
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Utility.packageNameToModuleName"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>packageNameToModuleName (package_name)](#apidoc.element.pm2.Utility.packageNameToModuleName)
- description and source-code
```javascript
packageNameToModuleName = function (package_name) {
  if (package_name.match(/^(.+\/)?([^\/]+)\.tgz($|\?)/)) {
    package_name = package_name.match(/^(.+\/)?([^\/]+)\.tgz($|\?)/)[2];
    if (package_name.match(/^(.+)-[0-9]+\.[0-9]+\.[0-9]+(-[a-zA-Z0-9_]+\.[0-9]+)?$/)) {
      package_name = package_name.match(/^(.+)-[0-9]+\.[0-9]+\.[0-9]+(-[a-zA-Z0-9_]+\.[0-9]+)?$/)[1];
    }
  }
  return package_name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Utility.startLogging"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>startLogging (stds, callback)](#apidoc.element.pm2.Utility.startLogging)
- description and source-code
```javascript
startLogging = function (stds, callback) {
<span class="apidocCodeCommentSpan">  /**
   * Start log outgoing messages
   * @method startLogging
   * @param {} callback
   * @return
   */
</span>  // Make sure directories of 'logs' and 'pids' exist.
  // try {
  //   ['logs', 'pids'].forEach(function(n){
  //     console.log(n);
  //     (function(_path){
  //       !fs.existsSync(_path) && fs.mkdirSync(_path, '0755');
  //     })(path.resolve(cst.PM2_ROOT_PATH, n));
  //   });
  // } catch(err) {
  //   return callback(new Error('can not create directories (logs/pids):' + err.message));
  // }

  // waterfall.
  var flows = [];
  // types of stdio, should be sorted as 'std(entire log)', 'out', 'err'.
  var types = Object.keys(stds).sort(function(x, y){
    return -x.charCodeAt(0) + y.charCodeAt(0);
  });

  // Create write streams.
  (function createWS(io){
    if(io.length != 1){
      return false;
    }
    io = io[0];

    // If 'std' is a Stream type, try next 'std'.
    // compatible with 'pm2 reloadLogs'
    if(typeof stds[io] == 'object' && !isNaN(stds[io].fd)){
      return createWS(types.splice(0, 1));
    }

    flows.push(function(next){
      var file = stds[io];
      // if file contains ERR or /dev/null, dont try to create stream since he dont want logs
      if (!file || file.indexOf('NULL') > -1 || file.indexOf('/dev/null') > -1)
        return next();
      stds[io] = fs.createWriteStream(file, {flags: 'a'})
        .on('error', function(err){
          next(err);
        })
        .on('open', function(){
          next();
        });
      stds[io]._file = file;
    });
    return createWS(types.splice(0, 1));
  })(types.splice(0, 1));

  async.waterfall(flows, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.Utility.whichFileExists"></a>[function <span class="apidocSignatureSpan">pm2.Utility.</span>whichFileExists (file_arr)](#apidoc.element.pm2.Utility.whichFileExists)
- description and source-code
```javascript
whichFileExists = function (file_arr) {
  var f = null;

  file_arr.some(function(file) {
    try {
      fs.statSync(file);
    } catch(e) {
      return false;
    }
    f = file;
    return true;
  });
  return f;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pm2.completion"></a>[module pm2.completion](#apidoc.module.pm2.completion)

#### <a name="apidoc.element.pm2.completion.complete"></a>[function <span class="apidocSignatureSpan">pm2.completion.</span>complete (name, completer, cb)](#apidoc.element.pm2.completion.complete)
- description and source-code
```javascript
function complete(name, completer, cb) {

  // cb not there, assume callback is completer and
  // the completer is the executable itself
  if(!cb) {
    cb = completer;
    completer = name;
  }

  var env = parseEnv();

  // if not a complete command, return here.
  if(!env.complete) return cb();

  // if install cmd, add complete script to either ~/.bashrc or ~/.zshrc
  if(env.install) return install(name, completer, function(err, state) {
    console.log(state || err.message);
    if(err) return cb(err);
    cb(null, null, state);
  });

  // if install cmd, add complete script to either ~/.bashrc or ~/.zshrc
  if(env.uninstall) return uninstall(name, completer, function(err, state) {
    console.log(state || err.message);
    if(err) return cb(err);
    cb(null, null, state);
  });

  // if the COMP_* are not in the env, then dump the install script.
  if(!env.words || !env.point || !env.line) return script(name, completer, function(err, content) {
    if(err) return cb(err);
    process.stdout.write(content, function (n) { cb(null, null, content); });
    process.stdout.on("error", function (er) {
      // Darwin is a real dick sometimes.
      //
      // This is necessary because the "source" or "." program in
      // bash on OS X closes its file argument before reading
      // from it, meaning that you get exactly 1 write, which will
      // work most of the time, and will always raise an EPIPE.
      //
      // Really, one should not be tossing away EPIPE errors, or any
      // errors, so casually.  But, without this, '. <(npm completion)'
      // can never ever work on OS X.
      //      -- isaacs
      // https://github.com/isaacs/npm/blob/master/lib/completion.js#L162
      if (er.errno === "EPIPE") er = null
      cb(er, null, content);
    });
    cb(null, null, content);
  });

  var partial = env.line.substr(0, env.point),
  last = env.line.split(' ').slice(-1).join(''),
  lastPartial = partial.split(' ').slice(-1).join(''),
  prev = env.line.split(' ').slice(0, -1).slice(-1)[0];

  cb(null, {
    line: env.line,
    words: env.words,
    point: env.point,
    partial: partial,
    last: last,
    prev: prev,
    lastPartial: lastPartial
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.completion.isComplete"></a>[function <span class="apidocSignatureSpan">pm2.completion.</span>isComplete ()](#apidoc.element.pm2.completion.isComplete)
- description and source-code
```javascript
function isComplete() {
  var env = parseEnv();
  return env.complete || (env.words && env.point && env.line);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.completion.log"></a>[function <span class="apidocSignatureSpan">pm2.completion.</span>log (arr, o, prefix)](#apidoc.element.pm2.completion.log)
- description and source-code
```javascript
function log(arr, o, prefix) {
  prefix = prefix || '';
  arr = Array.isArray(arr) ? arr : [arr];
  arr.filter(abbrev(o)).forEach(function(v) {
    console.log(prefix + v);
  });
}
```
- example usage
```shell
...

var daemon = new Daemon({
  pub_socket_file : that.conf.DAEMON_PUB_PORT,
  rpc_socket_file : that.conf.DAEMON_RPC_PORT,
  pid_file        : that.conf.PM2_PID_FILE_PATH
});

console.log('Launching in no daemon mode');

daemon.innerStart(function() {
  KMDaemon.launchAndInteract(that.conf, {
    machine_name : that.machine_name,
    public_key   : that.public_key,
    secret_key   : that.secret_key
  }, function(err, data, interactor_proc) {
...
```

#### <a name="apidoc.element.pm2.completion.parseOut"></a>[function <span class="apidocSignatureSpan">pm2.completion.</span>parseOut (str)](#apidoc.element.pm2.completion.parseOut)
- description and source-code
```javascript
function parseOut(str) {
  var shorts = str.match(/\s-\w+/g);
  var longs = str.match(/\s--\w+/g);

  return {
    shorts: shorts.map(trim).map(cleanPrefix),
    longs: longs.map(trim).map(cleanPrefix)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.completion.parseTasks"></a>[function <span class="apidocSignatureSpan">pm2.completion.</span>parseTasks (str, prefix, reg)](#apidoc.element.pm2.completion.parseTasks)
- description and source-code
```javascript
parseTasks = function (str, prefix, reg) {
  var tasks = str.match(reg || new RegExp('^' + prefix + '\\s[^#]+', 'gm')) || [];
  return tasks.map(trim).map(function(s) {
    return s.replace(prefix + ' ', '');
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pm2.custom"></a>[module pm2.custom](#apidoc.module.pm2.custom)

#### <a name="apidoc.element.pm2.custom.custom"></a>[function <span class="apidocSignatureSpan">pm2.</span>custom (opts)](#apidoc.element.pm2.custom.custom)
- description and source-code
```javascript
custom = function (opts) {
  if (!opts) opts = {};
  var that = this;

  this.daemon_mode = typeof(opts.daemon_mode) == 'undefined' ? true : opts.daemon_mode;
  this.pm2_home    = conf.PM2_ROOT_PATH;
  this.public_key   = process.env.KEYMETRICS_SECRET || opts.public_key || null;
  this.secret_key   = process.env.KEYMETRICS_PUBLIC || opts.secret_key || null;
  this.machine_name = process.env.INSTANCE_NAME || opts.machine_name || null

<span class="apidocCodeCommentSpan">  /**
   * CWD resolution
   */
</span>  this.cwd         = process.cwd();
  if (opts.cwd) {
    this.cwd = path.resolve(opts.cwd);
  }

  /**
   * PM2 HOME resolution
   */
  if (opts.pm2_home && opts.independent == true)
    throw new Error('You cannot set a pm2_home and independent instance in same time');

  if (opts.pm2_home) {
    // Override default conf file
    this.pm2_home        = opts.pm2_home;
    conf = util._extend(conf, path_structure(this.pm2_home));
  }
  else if (opts.independent == true && conf.IS_WINDOWS === false) {
    // Create an unique pm2 instance
    var crypto = require('crypto');
    var random_file = crypto.randomBytes(8).toString('hex');
    this.pm2_home = path.join('/tmp', random_file);

    // If we dont explicitly tell to have a daemon
    // It will go as in proc
    if (typeof(opts.daemon_mode) == 'undefined')
      this.daemon_mode = false;
    conf = util._extend(conf, path_structure(this.pm2_home));
  }

  this._conf = conf;

  if (conf.IS_WINDOWS) {
    // Weird fix, may need to be dropped
    // @todo windows connoisseur double check
    if (process.stdout._handle && process.stdout._handle.setBlocking)
      process.stdout._handle.setBlocking(true);
  }

  this.Client = new Client({
    pm2_home : that.pm2_home,
    conf     : this._conf,
    secret_key : this.secret_key,
    public_key : this.public_key,
    daemon_mode : this.daemon_mode,
    machine_name : this.machine_name
  });

  this.gl_interact_infos = null;
  this.gl_is_km_linked = false;

  try {
    var pid = fs.readFileSync(conf.INTERACTOR_PID_PATH);
    pid = parseInt(pid.toString().trim());
    process.kill(pid, 0);
    that.gl_is_km_linked = true;
  } catch(e) {
    that.gl_is_km_linked = false;
  }

  // For testing purposes
  if (this.secret_key && process.env.NODE_ENV == 'local_test')
    that.gl_is_km_linked = true;

  KMDaemon.getInteractInfo(this._conf, function(i_err, interact) {
    that.gl_interact_infos = interact;
  });
}
```
- example usage
```shell
...
var fmt       = require('./tools/fmt.js');
var exec      = require('child_process').exec;
var os        = require('os');

commander.version(pkg.version)
  .usage('[cmd] app');

var pm2 = new PM2.custom({
  pm2_home : path.join(os.homedir ? os.homedir() : (process.env.HOME || process.env.HOMEPATH || process.env.USERPROFILE), '.pm2-
dev')
});

pm2.connect(function() {
  commander.parse(process.argv);
});
...
```



# <a name="apidoc.module.pm2.custom.prototype"></a>[module pm2.custom.prototype](#apidoc.module.pm2.custom.prototype)

#### <a name="apidoc.element.pm2.custom.prototype._handleAttributeUpdate"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_handleAttributeUpdate (opts)](#apidoc.element.pm2.custom.prototype._handleAttributeUpdate)
- description and source-code
```javascript
_handleAttributeUpdate = function (opts) {
  var conf = Config.transCMDToConf(opts);
  var that = this;

  if (typeof(conf.name) != 'string')
    delete conf.name;

  var argsIndex = 0;
  if (opts.rawArgs && (argsIndex = opts.rawArgs.indexOf('--')) >= 0) {
    conf.args = opts.rawArgs.slice(argsIndex + 1);
  }

  var appConf = Common.verifyConfs(conf)[0];

  if (appConf instanceof Error) {
    Common.printError('Error while transforming CamelCase args to underscore');
    return appConf;
  }

  if (argsIndex == -1)
    delete appConf.args;
  if (appConf.name == 'undefined')
    delete appConf.name;

  delete appConf.exec_mode;

  if(util.isArray(appConf.watch) && appConf.watch.length === 0) {
    if(!~opts.rawArgs.indexOf('--watch'))
      delete appConf.watch
  }

  return appConf;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype._operate"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_operate (action_name, process_name, envs, cb)](#apidoc.element.pm2.custom.prototype._operate)
- description and source-code
```javascript
_operate = function (action_name, process_name, envs, cb) {
  var that = this;
  var update_env = false;
  var ret = [];

  // Make sure all options exist

  if (!envs)
    envs = {};

  if (typeof(envs) == 'function'){
    cb = envs;
    envs = {};
  }

  // Set via env.update (JSON processing)
  if (envs.updateEnv === true)
    update_env = true;

  if (!process.env.PM2_JSON_PROCESSING || envs.commands) {
    envs = that._handleAttributeUpdate(envs);
  }

<span class="apidocCodeCommentSpan">  /**
   * Set current updated configuration if not passed
   */
</span>  if (!envs.current_conf) {
    var _conf = fclone(envs);
    envs = {
      current_conf : _conf
    }

    // Is KM linked?
    envs.current_conf.km_link = that.gl_is_km_linked;
  }

  /**
   * Operate action on specific process id
   */
  function processIds(ids, cb) {
    Common.printOut(conf.PREFIX_MSG + 'Applying action %s on app [%s](ids: %s)', action_name, process_name, ids);

    var concurrent_actions = conf.CONCURRENT_ACTIONS;
    if (action_name == 'deleteProcessId')
      concurrent_actions = 10;

    async.eachLimit(ids, concurrent_actions, function(id, next) {
      var opts;

      // These functions need extra param to be passed
      if (action_name == 'restartProcessId' ||
          action_name == 'reloadProcessId' ||
          action_name == 'softReloadProcessId') {
        var new_env = {};

        if (update_env === true) {
          if (conf.PM2_PROGRAMMATIC == true)
            new_env = Common.safeExtend({}, process.env);
          else
            new_env = util._extend({}, process.env);

          Object.keys(envs).forEach(function(k) {
            new_env[k] = envs[k];
          });
        }
        else {
          new_env = envs;
        }

        opts = {
          id  : id,
          env : new_env
        };
      }
      else {
        opts = id;
      }

      that.Client.executeRemote(action_name, opts, function(err, res) {
        if (err) {
          Common.printError(conf.PREFIX_MSG_ERR + 'Process %s not found', id);
          return next('Process not found');
        }

        if (action_name == 'restartProcessId') {
          that.Client.notifyGod('restart', id);
        } else if (action_name == 'deleteProcessId') {
          that.Client.notifyGod('delete', id);
        } else if (action_name == 'stopProcessId') {
          that.Client.notifyGod('stop', id);
        } else if (action_name == 'reloadProcessId') {
          that.Client.notifyGod('reload', id);
        } else if (action_name == 'softReloadProcessId') {
          that.Client.notifyGod('graceful reload', id);
        }

        if (!Array.isArray(res))
          res = [res];

        // Filter return
        res.forEach(function(proc) {
          Common.printOut(conf.PREFIX_MSG + '[%s](%d) \u2713', proc.pm2_env ? proc.pm2_env.name : process_name, id);

          if (!proc.pm2_env) return false;

          ret.push({
            name         : proc.pm2_env.name,
            pm_id        : proc.pm2_env.pm_id,
            status       : proc.pm2_env.status,
            restart_time : proc.pm2_env.restart_time,
            pm2_env : {
              name         : proc.pm2_env.name,
              pm_id        : proc.pm2_env.pm_id,
              status       : proc.pm2_env.status,
              restart_time : proc.pm2_env.restart_time,
              env          : proc.pm2_env.env
            }
          });
        });

        return next();
      });
    }, function(err) {
      if (err) return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
      return cb ? cb(null, ret) : that.speedList();
    });
  }

  if (process_name == 'all') {
    that.Client.getAllProcessId(function(err, ids) {
      if (err) {
        Common.printError(err);
        return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
      }
      if (!ids || ids.length === 0) {
        Common.printError(conf.PREFIX_MSG_WARNING + 'No process found');
        return cb ? cb(new Error('process name not found')) : that.exitCli(conf.ERROR_EXIT);
      }

      return processIds(ids, cb);
    });
  }
  // operate using regex ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype._pre_interact"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_pre_interact (cmd, public_key, machine, info_node)](#apidoc.element.pm2.custom.prototype._pre_interact)
- description and source-code
```javascript
_pre_interact = function (cmd, public_key, machine, info_node) {
  var that = this;

  if (cmd == 'stop' || cmd == 'kill') {
    console.log(chalk.cyan('[Keymetrics.io]') + ' Stopping agent...');
    that.killInteract(function() {
      console.log(chalk.cyan('[Keymetrics.io]') + ' Stopped');
      return process.exit(cst.SUCCESS_EXIT);
    });
    return false;
  }

  if (cmd == 'info') {
    console.log(chalk.cyan('[Keymetrics.io]') + ' Getting agent information...');
    that.interactInfos(function(err, infos) {
      if (err) {
        console.error(err.message);
        return that.exitCli(cst.ERROR_EXIT);
      }
      console.log(infos);
      return that.exitCli(cst.SUCCESS_EXIT);
    });
    return false;
  }

  if (cmd == 'delete') {
    that.killInteract(function() {
      try {
        fs.unlinkSync(cst.INTERACTION_CONF);
      } catch(e) {
        console.log(chalk.cyan('[Keymetrics.io]') + ' No interaction config file found');
        return process.exit(cst.SUCCESS_EXIT);
      }
      console.log(chalk.cyan('[Keymetrics.io]') + ' Agent interaction ended');
      return process.exit(cst.SUCCESS_EXIT);
    });
    return false;
  }

  if (cmd == 'start' || cmd == 'restart') {
    KMDaemon.launchAndInteract(that._conf, {
      public_key : null,
      secret_key : null,
      machine_name : null,
      info_node : null
    }, function(err, dt) {
      if (err) {
        Common.printError(err);
        return that.exitCli(cst.ERROR_EXIT);
      }
      return that.exitCli(cst.SUCCESS_EXIT);
    });
  }

  if (cmd && !public_key) {
    console.error(chalk.cyan('[Keymetrics.io]') + ' Command [%s] unknown or missing public key', cmd);
    return process.exit(cst.ERROR_EXIT);
  }

  var infos;

  if (!cmd) {
    infos = null;
  }
  else
    infos = {
      public_key : public_key,
      secret_key : cmd,
      machine_name : machine,
      info_node : info_node.infoNode || null
    }

  KMDaemon.launchAndInteract(that._conf, infos, function(err, dt) {
    if (err)
      return that.exitCli(cst.ERROR_EXIT);
    return that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype._pull"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_pull (opts, cb)](#apidoc.element.pm2.custom.prototype._pull)
- description and source-code
```javascript
_pull = function (opts, cb) {
  var that = this;

  var process_name = opts.process_name;
  var reload_type = opts.action;

  printOut(cst.PREFIX_MSG + 'Updating repository for process name %s', process_name);

  that.Client.getProcessByName(process_name, function(err, processes) {

    if (processes.length === 0) {
      printError('No processes with this name: %s', process_name);
      return cb ? cb({msg:'Process not found: '+process_name}) : that.exitCli(cst.ERROR_EXIT);
    }

    var proc = processes[0];
    if (!proc.pm2_env.versioning) {
      printOut(cst.PREFIX_MSG + 'No versioning system found for process %s', process_name);
      return cb ? cb({success:false, msg: 'No versioning system found for process'}) : that.exitCli(cst.SUCCESS_EXIT);
    }
    vizion.update({
      folder: proc.pm2_env.versioning.repo_path
    }, function(err, meta) {
      if (err !== null) {
        return cb ? cb({msg:err}) : that.exitCli(cst.ERROR_EXIT);
      }

      if (meta.success === true) {
        getPostUpdateCmds(proc.pm2_env.versioning.repo_path, process_name, function (command_list) {
          execCommands(proc.pm2_env.versioning.repo_path, command_list, function(err, res) {
            if (err !== null) {
              printError(err);
              return cb ? cb({msg: meta.output + err}) : that.exitCli(cst.ERROR_EXIT);
            }
            else {
              printOut(cst.PREFIX_MSG + 'Process successfully updated %s', process_name);
              printOut(cst.PREFIX_MSG + 'Current commit %s', meta.current_revision);
              return that[reload_type](process_name, function(err, procs) {
                if (err && cb) return cb(err);
                if (err) console.error(err);
                return cb ? cb(null, meta.output + res) : that.exitCli(cst.SUCCESS_EXIT);
              });
            }
          });
        });
      }
      else {
        printOut(cst.PREFIX_MSG + 'Already up-to-date or an error occured for app: %s', process_name);
        return cb ? cb({success:false, msg : 'Already up to date'}) : that.exitCli(cst.SUCCESS_EXIT);
      }
      return false;
    });
    return false;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype._pullCommitId"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_pullCommitId (opts, cb)](#apidoc.element.pm2.custom.prototype._pullCommitId)
- description and source-code
```javascript
_pullCommitId = function (opts, cb) {
  this.pullCommitId(opts.pm2_name, opts.commit_id, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype._startJson"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_startJson (file, opts, action, pipe, cb)](#apidoc.element.pm2.custom.prototype._startJson)
- description and source-code
```javascript
_startJson = function (file, opts, action, pipe, cb) {
  var config     = {};
  var appConf    = {};
  var deployConf = {};
  var apps_info  = [];
  var that = this;

  if (typeof(cb) === 'undefined' && typeof(pipe) === 'function')
    cb = pipe;

  if (typeof(file) === 'object')
    config = file;
  else if (pipe == 'pipe')
    config = Common.parseConfig(file, 'pipe');
  else {
    var data = null;

    var file_path = path.join(that.cwd, file);

    if (file[0] == '/')
      file_path = file;

    debug('Resolved filepath %s', file_path);

    try {
      data = fs.readFileSync(file_path);
    } catch(e) {
      Common.printError(conf.PREFIX_MSG_ERR + 'File ' + file +' not found');
      return cb ? cb(Common.retErr(e)) : that.exitCli(conf.ERROR_EXIT);
    }

    try {
      config = Common.parseConfig(data, file);
    } catch(e) {
      Common.printError(conf.PREFIX_MSG_ERR + 'File ' + file + ' malformated');
      console.error(e);
      return cb ? cb(Common.retErr(e)) : that.exitCli(conf.ERROR_EXIT);
    }
  }

  if (config.deploy)
    deployConf = config.deploy;

  if (config.apps)
    appConf = config.apps;
  else
    appConf = config;

  if (!Array.isArray(appConf))
    appConf = [appConf]; //convert to array

  if ((appConf = Common.verifyConfs(appConf)) instanceof Error)
    return cb ? cb(appConf) : that.exitCli(conf.ERROR_EXIT);

  process.env.PM2_JSON_PROCESSING = true;

  // Get App list
  var apps_name = [];
  var proc_list = {};

  appConf.forEach(function(app) {
    if (opts.only && opts.only != app.name)
      return false;
    if (!app.watch && opts.watch && opts.watch === true)
      app.watch = true;
    if (!app.ignore_watch && opts.ignore_watch)
      app.ignore_watch = opts.ignore_watch;
    if (opts.instances && typeof(opts.instances) === 'number')
      app.instances = opts.instances;
    if (app.append_env_to_name && opts.env) {
      app.name += ('-' + opts.env);
    }
    apps_name.push(app.name);
  });

  that.Client.executeRemote('getMonitorData', {}, function(err, raw_proc_list) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
    }

<span class="apidocCodeCommentSpan">    /**
     * Uniquify in memory process list
     */
</span>    raw_proc_list.forEach(function(proc) {
      proc_list[proc.name] = proc;
    });

    /**
     * Auto detect application already started
     * and act on them depending on action
     */
    async.eachLimit(Object.keys(proc_list), conf.CONCURRENT_ACTIONS, function(proc_name, next) {
      // Skip app name (--only option)
      if (apps_name.indexOf(proc_name) == -1)
        return next();

      if (!(action == 'reloadProcessId' ||
            action == 'softReloadProcessId' ||
            action == 'restartProcessId'))
        throw new Error('Wrong action called');


      // Get 'env' from appConf by name
      async.filter(appConf, function(app, callback){
        callback(app.name == proc_name);
      }, function(apps){
        var envs = apps.map(function(app){
          // Binds env_diff to env and returns it.
          return Common.mergeEnvironmentVariables(app, opts.env, deployConf);
        });

        // Assigns own enumerable properties of all
        // Notice: if people use the same name in different apps,
        //         duplicated envs will be overrode by the last one
        var env = envs.reduce(function(e1, e2){
          return util._extend(e1, e2);
        });

        // When we are processing JSON, allow to keep the new env by default
        env.updateEnv = true;

        // Pass 'env' option
        that._operate(action, proc_name, env, function(err, ret) {
          if (err) Common.printError(err);

          // For return
          apps_info = apps_info.concat(ret);

          that.Client.notifyGod(action, proc_name);
          // And Remove from array to spy
          apps_name.splice(apps_name.indexOf(proc_name), 1);
          return next();
        });
      });

    }, function(err) {
      if (err) return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
      if (apps_name.length > 0 && actio ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype._startScript"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>_startScript (script, opts, cb)](#apidoc.element.pm2.custom.prototype._startScript)
- description and source-code
```javascript
_startScript = function (script, opts, cb) {
  if (typeof opts == "function") {
    cb = opts;
    opts = {};
  }
  var that = this;

  var app_conf = Config.transCMDToConf(opts);
  var appConf = {};

  if (!!opts.executeCommand)
    app_conf.exec_mode = 'fork';
  else if (opts.instances !== undefined)
    app_conf.exec_mode = 'cluster';
  else
    app_conf.exec_mode = 'fork';

  if (typeof app_conf.name == 'function'){
    delete app_conf.name;
  }

  delete app_conf.args;

  var argsIndex;

  if (opts.rawArgs && (argsIndex = opts.rawArgs.indexOf('--')) >= 0) {
    app_conf.args = opts.rawArgs.slice(argsIndex + 1);
  }
  else if (opts.scriptArgs) {
    app_conf.args = opts.scriptArgs;
  }

  app_conf.script = script;

  if ((appConf = Common.verifyConfs(app_conf)) instanceof Error)
    return cb ? cb(Common.retErr(appConf)) : that.exitCli(conf.ERROR_EXIT);

  app_conf = appConf[0];

<span class="apidocCodeCommentSpan">  /**
   * If -w option, write configuration to configuration.json file
   */
</span>  if (appConf.write) {
    var dst_path = path.join(process.env.PWD || process.cwd(), app_conf.name + '-pm2.json');
    Common.printOut(conf.PREFIX_MSG + 'Writing configuration to', chalk.blue(dst_path));
    // pretty JSON
    try {
      fs.writeFileSync(dst_path, JSON.stringify(app_conf, null, 2));
    } catch (e) {
      console.error(e.stack || e);
    }
  }

  /**
   * If start <app_name> start/restart application
   */
  function restartExistingProcessName(cb) {
    if (!isNaN(script) ||
        (typeof script === 'string' && script.indexOf('/') != -1) ||
        (typeof script === 'string' && path.extname(script) !== ''))
      return cb(null);

    if (script !== 'all') {
      that.Client.getProcessIdByName(script, function(err, ids) {
        if (err && cb) return cb(err);
        if (ids.length > 0) {
          that._operate('restartProcessId', script, opts, function(err, list) {
            if (err) return cb(err);
            Common.printOut(conf.PREFIX_MSG + 'Process successfully started');
            return cb(true, list);
          });
        }
        else return cb(null);
      });
    }
    else {
      that._operate('restartProcessId', 'all', function(err, list) {
        if (err) return cb(err);
        Common.printOut(conf.PREFIX_MSG + 'Process successfully started');
        return cb(true, list);
      });
    }
  }

  function restartExistingProcessId(cb) {
    if (isNaN(script)) return cb(null);

    that._operate('restartProcessId', script, opts, function(err, list) {
      if (err) return cb(err);
      Common.printOut(conf.PREFIX_MSG + 'Process successfully started');
      return cb(true, list);
    });
  }

  /**
   * Restart a process with the same full path
   * Or start it
   */
  function restartExistingProcessPath(cb) {
    that.Client.executeRemote('getMonitorData', {}, function(err, procs) {
      if (err) return cb ? cb(new Error(err)) : that.exitCli(conf.ERROR_EXIT);

      var full_path = path.resolve(that.cwd, script);
      var managed_script = null;

      procs.forEach(function(proc) {
        if (proc.pm2_env.pm_exec_path == full_path &&
            proc.pm2_env.name == app_conf.name)
          managed_script = proc;
      });

      if (managed_script &&
          (managed_script.pm2_env.status == conf.STOPPED_STATUS ||
           managed_script.pm2_env.status == conf.STOPPING_STATUS ||
           managed_script.pm2_env.status == conf.ERRORED_STATUS)) {
        // Restart process if stopped
        var app_name = managed_script.pm2_env.name;

        that._operate('restartProcessId', app_name, opts, function(err, list) {
          if (err) return cb ? cb(new Error(err)) : that.exitCli(conf.ERROR_EXIT);
          Common.printOut(conf.PREFIX_MSG + 'Process successfully started');
          return cb(true, list);
        });
        return false;
      }
      else if (managed_script && !opts.force) {
        Common.printError(conf.PREFIX_MSG_ERR + 'Script already launched, add -f option to force re-execution');
        return cb(new Error('Script already launched'));
      }

      var resolved_paths = null;

      try {
        res ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.actionFromJson"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>actionFromJson (action, file, opts, jsonVia, cb)](#apidoc.element.pm2.custom.prototype.actionFromJson)
- description and source-code
```javascript
actionFromJson = function (action, file, opts, jsonVia, cb) {
  var appConf = {};
  var ret_processes = [];
  var that = this;

  //accept programmatic calls
  if (typeof file == 'object') {
    cb = typeof jsonVia == 'function' ? jsonVia : cb;
    appConf = file;
  }
  else if (jsonVia == 'file') {
    var data = null;

    try {
      data = fs.readFileSync(file);
    } catch(e) {
      Common.printError(conf.PREFIX_MSG_ERR + 'File ' + file +' not found');
      return cb ? cb(Common.retErr(e)) : that.exitCli(conf.ERROR_EXIT);
    }

    try {
      appConf = Common.parseConfig(data, file);
    } catch(e) {
      Common.printError(conf.PREFIX_MSG_ERR + 'File ' + file + ' malformated');
      console.error(e);
      return cb ? cb(Common.retErr(e)) : that.exitCli(conf.ERROR_EXIT);
    }
  } else if (jsonVia == 'pipe') {
    appConf = Common.parseConfig(file, 'pipe');
  } else {
    Common.printError('Bad call to actionFromJson, jsonVia should be one of file, pipe');
    return that.exitCli(conf.ERROR_EXIT);
  }

  // Backward compatibility
  if (appConf.apps)
    appConf = appConf.apps;

  if (!Array.isArray(appConf))
    appConf = [appConf];

  if ((appConf = Common.verifyConfs(appConf)) instanceof Error)
    return cb ? cb(appConf) : that.exitCli(conf.ERROR_EXIT);

  async.eachLimit(appConf, conf.CONCURRENT_ACTIONS, function(proc, next1) {
    var name = '';
    var new_env;

    if (!proc.name)
      name = path.basename(proc.script);
    else
      name = proc.name;

    if (opts.only && opts.only != name)
      return process.nextTick(next1);

    if (opts && opts.env)
      new_env = Common.mergeEnvironmentVariables(proc, opts.env);
    else
      new_env = Common.mergeEnvironmentVariables(proc);

    that.Client.getProcessIdByName(name, function(err, ids) {
      if (err) {
        Common.printError(err);
        return next1();
      }
      if (!ids) return next1();

      async.eachLimit(ids, conf.CONCURRENT_ACTIONS, function(id, next2) {
        var opts = {};

        //stopProcessId could accept options to?
        if (action == 'restartProcessId') {
          opts = {id : id, env : new_env};
        } else {
          opts = id;
        }

        that.Client.executeRemote(action, opts, function(err, res) {
          ret_processes.push(res);
          if (err) {
            Common.printError(err);
            return next2();
          }

          if (action == 'restartProcessId') {
            that.Client.notifyGod('restart', id);
          } else if (action == 'deleteProcessId') {
            that.Client.notifyGod('delete', id);
          } else if (action == 'stopProcessId') {
            that.Client.notifyGod('stop', id);
          }

          Common.printOut(conf.PREFIX_MSG + '[%s](%d) \u2713', name, id);
          return next2();
        });
      }, function(err) {
        return next1(null, ret_processes);
      });
    });
  }, function(err) {
    if (cb) return cb(null, ret_processes);
    else return that.speedList();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.backward"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>backward (process_name, cb)](#apidoc.element.pm2.custom.prototype.backward)
- description and source-code
```javascript
backward = function (process_name, cb) {
  var that = this;
  printOut(cst.PREFIX_MSG + 'Downgrading to previous commit repository for process name %s', process_name);

  that.Client.getProcessByName(process_name, function(err, processes) {

    if (processes.length === 0) {
      printError('No processes with this name: %s', process_name);
      return cb ? cb({msg:'Process not found: '+process_name}) : that.exitCli(cst.ERROR_EXIT);
    }

    var proc = processes[0];

    if (proc.pm2_env.versioning === undefined ||
        proc.pm2_env.versioning === null)
      return cb({msg : 'Versioning unknown'});

    vizion.prev({
      folder: proc.pm2_env.versioning.repo_path
    }, function(err, meta) {
      if (err)
        return cb ? cb({msg:err, data : meta}) : that.exitCli(cst.ERROR_EXIT);

      if (meta.success !== true) {
        printOut(cst.PREFIX_MSG + 'No versioning system found for process %s', process_name);
        return cb ? cb({msg:err, data : meta}) : that.exitCli(cst.ERROR_EXIT);;
      }

      getPostUpdateCmds(proc.pm2_env.versioning.repo_path, process_name, function (command_list) {
        execCommands(proc.pm2_env.versioning.repo_path, command_list, function(err, res) {
          if (err !== null) {
            vizion.next({folder: proc.pm2_env.versioning.repo_path}, function(err2, meta2) {
              printError(err);
              return cb ? cb({msg: meta.output + err}) : that.exitCli(cst.ERROR_EXIT);
            });
            return false;
          }

          printOut(cst.PREFIX_MSG + 'Process successfully updated %s', process_name);
          printOut(cst.PREFIX_MSG + 'Current commit %s', meta.current_revision);
          that.reload(process_name, function(err, procs) {
            if (err) return cb(err);
            return cb ? cb(null, meta.output + res) : that.exitCli(cst.SUCCESS_EXIT);
          });
        });
      });
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.close"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>close (cb)](#apidoc.element.pm2.custom.prototype.close)
- description and source-code
```javascript
close = function (cb) {
  var that = this;

  if (!cb) cb = function() {};

  this.Client.close(function(err, data) {
    debug('The session lasted %ds', (new Date() - that.start_timer) / 1000);
    return cb(err, data);
  });
}
```
- example usage
```shell
...
Client.prototype.pingDaemon = function pingDaemon(cb) {
var req    = axon.socket('req');
var client = new rpc.Client(req);

debug('[PING PM2] Trying to connect to server');

client.sock.once('reconnect attempt', function() {
  client.sock.close();
  debug('Daemon not launched');
  process.nextTick(function() {
    return cb(false);
  });
});

client.sock.once('connect', function() {
...
```

#### <a name="apidoc.element.pm2.custom.prototype.conf"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>conf (key, value, cb)](#apidoc.element.pm2.custom.prototype.conf)
- description and source-code
```javascript
conf = function (key, value, cb) {
  var that = this;

  if (typeof(value) === 'function') {
    cb = value;
    value = null;
  }

  // If key + value = set
  if (key && value) {
    that.set(key, value, function(err) {
      if (err)
        return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
      return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
    });
  }
  // If only key = get
  else if (key) {
    that.get(key, function(err, data) {
      if (err)
        return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
      return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
    });
  }
  else {
    displayConf(function(err, data) {
      if (err)
        return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
      return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.connect"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>connect (noDaemon, cb)](#apidoc.element.pm2.custom.prototype.connect)
- description and source-code
```javascript
connect = function (noDaemon, cb) {
  var that = this;
  this.start_timer = new Date();

  if (typeof(cb) == 'undefined') {
    cb = noDaemon;
    noDaemon = false;
  } else if (noDaemon === true) {
    // Backward compatibility with PM2 1.x
    this.Client.daemon_mode = false;
    this.daemon_mode = false;
  }

  this.Client.start(function(err, meta) {
    if (err)
      return cb(err);

    if (meta.new_pm2_instance == false && that.daemon_mode === true)
      return cb(err, meta);

    // If new pm2 instance has been popped
    // Lauch all modules
    Modularizer.launchAll(that, function(err_mod) {
      return cb(err, meta);
    });
  });
}
```
- example usage
```shell
...
   client.sock.once('close', function() {
     return cb(true);
   });
   client.sock.close();
   debug('Daemon alive');
 });

 req.connect(this.rpc_socket_file);
};

/**
* Methods to interact with the Daemon via RPC
* This method wait to be connected to the Daemon
* Once he's connected it trigger the command parsing (on ./bin/pm2 file, at the end)
* @method launchRPC
...
```

#### <a name="apidoc.element.pm2.custom.prototype.dashboard"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>dashboard (cb)](#apidoc.element.pm2.custom.prototype.dashboard)
- description and source-code
```javascript
dashboard = function (cb) {
  var that = this;

  var Dashboard = require('./Dashboard');

  if (cb) return cb(new Error('Dashboard cant be called programmatically'));

  Dashboard.init();

  this.Client.launchBus(function (err, bus) {
    if (err) {
        console.error('Error launchBus: ' + err);
        that.exitCli(cst.ERROR_EXIT);
    }
    bus.on('log:*', function(type, data) {
      Dashboard.log(type, data);
    })
  });

  process.on('SIGINT', function() {
    this.Client.disconnectBus(function() {
      process.exit(cst.SUCCESS_EXIT);
    });
  });

  function launchDashboard() {
    that.Client.executeRemote('getMonitorData', {}, function(err, list) {
      if (err) {
        console.error('Error retrieving process list: ' + err);
        that.exitCli(cst.ERROR_EXIT);
      }

      Dashboard.refresh(list);

      setTimeout(function() {
        launchDashboard();
      }, 800);
    });
  }

  launchDashboard();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.deepUpdate"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>deepUpdate (cb)](#apidoc.element.pm2.custom.prototype.deepUpdate)
- description and source-code
```javascript
deepUpdate = function (cb) {
  var that = this;

  Common.printOut(conf.PREFIX_MSG + 'Updating PM2...');

  var exec = require('shelljs').exec;
  var child = exec("npm i -g pm2@latest; pm2 update", {async : true});

  child.stdout.on('end', function() {
    Common.printOut(conf.PREFIX_MSG + 'PM2 successfully updated');
    cb ? cb(null, {success:true}) : that.exitCli(conf.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.delete"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>delete (process_name, jsonVia, cb)](#apidoc.element.pm2.custom.prototype.delete)
- description and source-code
```javascript
delete = function (process_name, jsonVia, cb) {
  var that = this;

  if (typeof(jsonVia) === "function") {
    cb = jsonVia;
    jsonVia = null;
  }
  if (typeof(process_name) === "number") {
    process_name = process_name.toString();
  }

  if (jsonVia == 'pipe')
    return that.actionFromJson('deleteProcessId', process_name, commander, 'pipe', cb);
  if (Common.isConfigFile(process_name))
    return that.actionFromJson('deleteProcessId', process_name, commander, 'file', cb);
  else
    that._operate('deleteProcessId', process_name, cb);
}
```
- example usage
```shell
...
    return cb(new Error('v8-profiler is not available'));
  }

  var snapshot1 = profiler.takeSnapshot();
  var path = require('path');
  snapshot1.export(function(error, result) {
    fs.writeFile(msg.pwd, result, function() {
      snapshot1.delete();
      return cb(null, {file : msg.pwd});
    });
  });
}

function startProfilingPM2(msg, cb) {
  if (profiler == null) {
...
```

#### <a name="apidoc.element.pm2.custom.prototype.deleteModule"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>deleteModule (module_name, cb)](#apidoc.element.pm2.custom.prototype.deleteModule)
- description and source-code
```javascript
deleteModule = function (module_name, cb) {
  var that = this;

  var found_proc = [];

  this.Client.getAllProcess(function(err, procs) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      return cb(Common.retErr(err));
    }

    procs.forEach(function(proc) {
      if (proc.pm2_env.name == module_name && proc.pm2_env.pmx_module) {
        found_proc.push(proc.pm_id);
      }
    });

    if (found_proc.length == 0)
      return cb();

    that._operate('deleteProcessId', found_proc[0], function(err) {
      if (err) return cb(Common.retErr(err));
      Common.printOut('In memory process deleted');
      return cb();
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.deploy"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>deploy (file, commands, cb)](#apidoc.element.pm2.custom.prototype.deploy)
- description and source-code
```javascript
deploy = function (file, commands, cb) {
  var that = this;

  if (file == 'help') {
    deployHelper();
    return cb ? cb() : that.exitCli(cst.SUCCESS_EXIT);
  }

  var args = commands.rawArgs;
  var env;

  args.splice(0, args.indexOf('deploy') + 1);

  // Find ecosystem file by default
  if (!Common.isConfigFile(file)) {
    env = args[0];
    file = Utility.whichFileExists(['ecosystem.config.js', 'ecosystem.json', 'ecosystem.json5', 'package.json']);

    if (!file) {
      Common.printError('Not any default deployment file exists');
      return cb ? cb('Not any default ecosystem file present') : that.exitCli(cst.ERROR_EXIT);
    }
  }
  else
    env = args[1];

  var json_conf = null;

  try {
    json_conf = Common.parseConfig(fs.readFileSync(file), file);
  } catch (e) {
    Common.printError(e);
    return cb ? cb(e) : that.exitCli(cst.ERROR_EXIT);
  }

  if (!env) {
    deployHelper();
    return cb ? cb() : that.exitCli(cst.SUCCESS_EXIT);
  }

  if (!json_conf.deploy || !json_conf.deploy[env]) {
    Common.printError('%s environment is not defined in %s file', env, file);
    return cb ? cb('%s environment is not defined in %s file') : that.exitCli(cst.ERROR_EXIT);
  }

  if (!json_conf.deploy[env]['post-deploy']) {
    json_conf.deploy[env]['post-deploy'] = 'pm2 startOrRestart ' + file + ' --env ' + env;
  }

  Deploy.deployForEnv(json_conf.deploy, env, args, function(err, data) {
    if (err) {
      Common.printError('Deploy failed');
      return cb ? cb(err) : that.exitCli(cst.ERROR_EXIT);
    }
    Common.printOut('--> Success');
    return cb ? cb(null, data) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.describe"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>describe (pm2_id, cb)](#apidoc.element.pm2.custom.prototype.describe)
- description and source-code
```javascript
describe = function (pm2_id, cb) {
  var that = this;

  var found_proc = [];

  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      that.exitCli(conf.ERROR_EXIT);
    }

    list.forEach(function(proc) {
      if ((!isNaN(pm2_id)    && proc.pm_id == pm2_id) ||
          (typeof(pm2_id) === 'string' && proc.name  == pm2_id)) {
        found_proc.push(proc);
      }
    });

    if (found_proc.length === 0) {
      Common.printError(conf.PREFIX_MSG_WARNING + '%s doesn\'t exist', pm2_id);
      return cb ? cb(null, []) : that.exitCli(conf.ERROR_EXIT);
    }

    if (!cb) {
      found_proc.forEach(function(proc) {
        UX.describeTable(proc);
      });
    }

    return cb ? cb(null, found_proc) : that.exitCli(conf.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.destroy"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>destroy (cb)](#apidoc.element.pm2.custom.prototype.destroy)
- description and source-code
```javascript
destroy = function (cb) {
  var exec = require('shelljs').exec;
  var that = this;

  debug('Killing and deleting current deamon');

  this.killDaemon(function() {
    var cmd = 'rm -rf ' + that.pm2_home;
    var test_path = path.join(that.pm2_home, 'module_conf.json');
    var test_path_2 = path.join(that.pm2_home, 'pm2.pid');

    if (that.pm2_home.indexOf('.pm2') > -1)
      return cb(new Error('Destroy is not a allowed method on .pm2'));

    if (fs.accessSync) {
      fs.access(test_path, fs.R_OK, function(err) {
        if (err) return cb(err);
        debug('Deleting temporary folder %s', that.pm2_home);
        exec(cmd, cb);
      });
      return false;
    }

    // Support for Node 0.10
    fs.exists(test_path, function(exist) {
      if (exist) {
        debug('Deleting temporary folder %s', that.pm2_home);
        exec(cmd, cb);
      }
      return cb(null);
    });
  });
}
```
- example usage
```shell
...
    that.client = null;
    debug('PM2 RPC cleanly closed');
    return cb(null, { msg : 'RPC Successfully closed' });
  });

  timer = setTimeout(function() {
    if (Client.client_sock.destroy)
      that.client_sock.destroy();
    that.client = null;
    return cb(null, { msg : 'RPC Successfully closed via timeout' });
  }, 200);

  that.client_sock.close();
} catch(e) {
  debug('Error while disconnecting RPC PM2', e.stack || e);
...
```

#### <a name="apidoc.element.pm2.custom.prototype.disconnect"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>disconnect (cb)](#apidoc.element.pm2.custom.prototype.disconnect)
- description and source-code
```javascript
disconnect = function (cb) {
  var that = this;

  if (!cb) cb = function() {};

  this.Client.close(function(err, data) {
    debug('The session lasted %ds', (new Date() - that.start_timer) / 1000);
    return cb(err, data);
  });
}
```
- example usage
```shell
...
  child.once('error', onError);

  child.unref();

  child.once('message', function(msg) {
debug('PM2 daemon launched with return message: ', msg);
child.removeListener('error', onError);
child.disconnect();

if (opts && opts.interactor == false)
  return cb(null, child);

/**
 * Here the Keymetrics agent is launched automaticcaly if
 * it has been already configured before (via pm2 link)
...
```

#### <a name="apidoc.element.pm2.custom.prototype.dockerMode"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>dockerMode (script, opts, mode)](#apidoc.element.pm2.custom.prototype.dockerMode)
- description and source-code
```javascript
dockerMode = function (script, opts, mode) {
  var self = this;
  handleExit(self, opts, mode);

  if (mode == 'distribution' && !opts.imageName) {
    return console.error(chalk.bold.red('--image-name [name] option is missing'));
  }

  var template;
  var app_path, main_script;
  var image_name;

  image_name   = opts.imageName || crypto.randomBytes(6).toString('hex');

  if (script.indexOf('/') > -1) {
    app_path  = path.join(process.cwd(), path.dirname(script));
    main_script = path.basename(script);
  }
  else {
    app_path  = process.cwd();
    main_script = script;
  }

  checkDockerSetup()
    .then(function() {
      /////////////////////////
      // Generate Dockerfile //
      /////////////////////////
      return new Promise(function(resolve, reject) {
        var docker_filepath = path.join(process.cwd(), 'Dockerfile');

        fs.stat(docker_filepath, function(err, stat) {
          if (err) {
            // Dockerfile does not exists, generate one
            console.log(chalk.blue.bold('Generating new Dockerfile'));
            return resolve(generateDockerfile(docker_filepath, main_script, mode));
          }
          return resolve(switchDockerFile(docker_filepath, main_script, mode));
        });
      });
    })
    .then(function(_template) {
      template = _template;
      return Promise.resolve();
    })
    .then(function() {
      //////////////////
      // Docker build //
      //////////////////

      var docker_build = util.format('docker build -t %s -f %s',
                                     image_name,
                                     template.Dockerfile_path);

      if (opts.fresh == true)
        docker_build += ' --no-cache';
      docker_build += ' .';

      console.log();
      fmt.sep();
      fmt.title('Building Boot System');
      fmt.field('Type', chalk.cyan.bold('Docker'));
      fmt.field('Mode', mode);
      fmt.field('Image name', image_name);
      fmt.field('Docker build command', docker_build);
      fmt.field('Dockerfile path', template.Dockerfile_path);
      fmt.sep();

      return pspawn(docker_build);
    })
    .then(function() {
      ////////////////
      // Docker run //
      ////////////////

      var docker_run = 'docker run --net host';

      if (opts.daemon == true)
        docker_run += ' -d';
      if (mode != 'distribution')
        docker_run += util.format(' -v %s:/var/app -v /var/app/node_modules', app_path);
      docker_run += ' ' + image_name;

      console.log();
      fmt.sep();
      fmt.title('Booting');
      fmt.field('Type', chalk.cyan.bold('Docker'));
      fmt.field('Mode', mode);
      fmt.field('Image name', image_name);
      fmt.field('Docker run command', docker_run);
      fmt.field('Docker main CMD', template.CMD);
      fmt.field('CWD', app_path);
      fmt.sep();
      return pspawn(docker_run);
    })
    .then(function() {
      console.log(chalk.blue.bold('>>> Leaving Docker instance uuid=%s'), image_name);
      self.disconnect();
      return Promise.resolve();
    })
    .catch(function(err) {
      console.log();
      console.log(chalk.grey('Raw error=', err.message));
      self.disconnect();
    });

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.dump"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>dump (cb)](#apidoc.element.pm2.custom.prototype.dump)
- description and source-code
```javascript
dump = function (cb) {
  var env_arr = [];
  var that = this;


  Common.printOut(cst.PREFIX_MSG + 'Saving current process list...');

  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError('Error retrieving process list: ' + err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }

<span class="apidocCodeCommentSpan">    /**
     * Description
     * @method fin
     * @param {} err
     * @return
     */
</span>    function fin(err) {
      try {
        fs.writeFileSync(cst.DUMP_FILE_PATH, JSON.stringify(env_arr, '', 2));
      } catch (e) {
        console.error(e.stack || e);
        Common.printOut(cst.PREFIX_MSG_ERR + 'Failed to save dump file in %s', cst.DUMP_FILE_PATH);
        return that.exitCli(cst.ERROR_EXIT);
      }
      if (cb) return cb(null, {success:true});

      Common.printOut(cst.PREFIX_MSG + 'Successfully saved in %s', cst.DUMP_FILE_PATH);
      return that.exitCli(cst.SUCCESS_EXIT);
    }

    (function ex(apps) {
      if (!apps[0]) return fin(null);
      delete apps[0].pm2_env.instances;
      delete apps[0].pm2_env.pm_id;
      if (!apps[0].pm2_env.pmx_module)
        env_arr.push(apps[0].pm2_env);
      apps.shift();
      return ex(apps);
    })(list);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.exitCli"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>exitCli (code)](#apidoc.element.pm2.custom.prototype.exitCli)
- description and source-code
```javascript
exitCli = function (code) {
  var that = this;

  // Do nothing if PM2 called programmatically (also in speedlist)
  if (conf.PM2_PROGRAMMATIC && process.env.PM2_USAGE != 'CLI') return false;

  KMDaemon.disconnectRPC(function() {
    that.Client.close(function() {
      code = code || 0;
      // Safe exits process after all streams are drained.
      // file descriptor flag.
      var fds = 0;
      // exits process when stdout (1) and sdterr(2) are both drained.
      function tryToExit() {
        if ((fds & 1) && (fds & 2)) {
          debug('This command took %ds to execute', (new Date() - that.start_timer) / 1000);
          process.exit(code);
        }
      }

      [process.stdout, process.stderr].forEach(function(std) {
        var fd = std.fd;
        if (!std.bufferSize) {
          // bufferSize equals 0 means current stream is drained.
          fds = fds | fd;
        } else {
          // Appends nothing to the std queue, but will trigger 'tryToExit' event on 'drain'.
          std.write && std.write('', function() {
            fds = fds | fd;
            tryToExit();
          });
        }
        // Does not write anything more.
        delete std.write;
      });
      tryToExit();
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.flush"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>flush (cb)](#apidoc.element.pm2.custom.prototype.flush)
- description and source-code
```javascript
flush = function (cb) {
  var that = this;

  Common.printOut(cst.PREFIX_MSG + 'Flushing ' + cst.PM2_LOG_FILE_PATH);
  fs.closeSync(fs.openSync(cst.PM2_LOG_FILE_PATH, 'w'));

  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    list.forEach(function(l) {
      Common.printOut(cst.PREFIX_MSG + 'Flushing');
      Common.printOut(cst.PREFIX_MSG + l.pm2_env.pm_out_log_path);
      Common.printOut(cst.PREFIX_MSG + l.pm2_env.pm_err_log_path);

      if (l.pm2_env.pm_log_path) {
        Common.printOut(cst.PREFIX_MSG + l.pm2_env.pm_log_path);
        fs.closeSync(fs.openSync(l.pm2_env.pm_log_path, 'w'));
      }

      fs.closeSync(fs.openSync(l.pm2_env.pm_out_log_path, 'w'));
      fs.closeSync(fs.openSync(l.pm2_env.pm_err_log_path, 'w'));
    });
    Common.printOut(cst.PREFIX_MSG + 'Logs flushed');
    return cb ? cb(null, list) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.forward"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>forward (process_name, cb)](#apidoc.element.pm2.custom.prototype.forward)
- description and source-code
```javascript
forward = function (process_name, cb) {
  var that = this;
  printOut(cst.PREFIX_MSG + 'Updating to next commit repository for process name %s', process_name);

  that.Client.getProcessByName(process_name, function(err, processes) {

    if (processes.length === 0) {
      printError('No processes with this name: %s', process_name);
      return cb ? cb({msg:'Process not found: '+process_name}) : that.exitCli(cst.ERROR_EXIT);
    }

    var proc = processes[0];
    if (proc.pm2_env.versioning) {
      vizion.next({folder: proc.pm2_env.versioning.repo_path}, function(err, meta) {
        if (err !== null)
          return cb ? cb({msg:err}) : that.exitCli(cst.ERROR_EXIT);
        if (meta.success === true) {
          getPostUpdateCmds(proc.pm2_env.versioning.repo_path, process_name, function (command_list) {
            execCommands(proc.pm2_env.versioning.repo_path, command_list, function(err, res) {
              if (err !== null)
              {
                vizion.prev({folder: proc.pm2_env.versioning.repo_path}, function(err2, meta2) {
                  printError(err);
                  return cb ? cb({msg:meta.output + err}) : that.exitCli(cst.ERROR_EXIT);
                });
              }
              else {
                printOut(cst.PREFIX_MSG + 'Process successfully updated %s', process_name);
                printOut(cst.PREFIX_MSG + 'Current commit %s', meta.current_revision);
                that.reload(process_name, function(err, procs) {
                  if (err) return cb(err);
                  return cb ? cb(null, meta.output + res) : that.exitCli(cst.SUCCESS_EXIT);
                });
              }
            });
          });
        }
        else {
          printOut(cst.PREFIX_MSG + 'Already up-to-date or an error occured: %s', process_name);
          return cb ? cb(null, {success:meta.success}) : that.exitCli(cst.SUCCESS_EXIT);
        }
      });
    }
    else {
      printOut(cst.PREFIX_MSG + 'No versioning system found for process %s', process_name);
      return cb ? cb({success:false, msg: 'No versioning system found'}) : that.exitCli(cst.SUCCESS_EXIT);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.generateDockerfile"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>generateDockerfile (script, opts)](#apidoc.element.pm2.custom.prototype.generateDockerfile)
- description and source-code
```javascript
generateDockerfile = function (script, opts) {
  var docker_filepath = path.join(process.cwd(), 'Dockerfile');
  var that = this;

  fs.stat(docker_filepath, function(err, stat) {
    if (err || opts.force == true) {
      generateDockerfile(docker_filepath, script, 'development')
        .then(function() {
          console.log(chalk.bold('New Dockerfile generated in current folder'));
          console.log(chalk.bold('You can now run\n$ pm2 docker:dev <file|config>'));
          return that.exitCli(cst.SUCCESS_EXIT);
        });
      return false;
    }
    console.log(chalk.red.bold('Dockerfile already exists in this folder, use --force if you want to replace it'));
    that.exitCli(cst.ERROR_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.generateModuleSample"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>generateModuleSample (app_name, cb)](#apidoc.element.pm2.custom.prototype.generateModuleSample)
- description and source-code
```javascript
generateModuleSample = function (app_name, cb) {
  var that = this;

  Modularizer.generateSample(app_name, function(err, data) {
    if (err)
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    return cb ? cb(null, data) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.generateSample"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>generateSample (mode)](#apidoc.element.pm2.custom.prototype.generateSample)
- description and source-code
```javascript
generateSample = function (mode) {
  var that = this;
  var templatePath;

  if (mode == 'simple')
    templatePath = path.join(cst.TEMPLATE_FOLDER, cst.APP_CONF_TPL_SIMPLE);
  else
    templatePath = path.join(cst.TEMPLATE_FOLDER, cst.APP_CONF_TPL);

  var sample = fs.readFileSync(templatePath);
  var dt     = sample.toString();
  var f_name = 'ecosystem.config.js';
		var pwd = process.env.PWD || process.cwd();

  try {
    fs.writeFileSync(path.join(pwd, f_name), dt);
  } catch (e) {
    console.error(e.stack || e);
    return that.exitCli(cst.ERROR_EXIT);
  }
  Common.printOut('File %s generated', path.join(pwd, f_name));
  that.exitCli(cst.SUCCESS_EXIT);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.get"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>get (key, cb)](#apidoc.element.pm2.custom.prototype.get)
- description and source-code
```javascript
get = function (key, cb) {
  var that = this;

  if (!key || key == 'all') {
    that.displayConf(function(err, data) {
      if (err)
        return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
      return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
    });
    return false;
  }
  Configuration.get(key, function(err, data) {
    if (err) {
      console.error(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    // pm2 conf module-name
    if (key.indexOf(':') === -1 && key.indexOf('.') === -1) {
      displayConf(key, function() {
        return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
      });
      return false;
    }
    // pm2 conf module-name:key
    var module_name, key_name;

    if (key.indexOf(':') > -1) {
      module_name = key.split(':')[0];
      key_name    = key.split(':')[1];
    } else if (key.indexOf('.') > -1) {
      module_name = key.split('.')[0];
      key_name    = key.split('.')[1];
    }

    Common.printOut('Value for module ' + chalk.blue(module_name), 'key ' + chalk.blue(key_name) + ': ' + chalk.bold.green(data));


    return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.getProcessIdByName"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>getProcessIdByName (name, cb)](#apidoc.element.pm2.custom.prototype.getProcessIdByName)
- description and source-code
```javascript
getProcessIdByName = function (name, cb) {
  var that = this;

  this.Client.getProcessIdByName(name, function(err, id) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
    }
    console.log(id);
    return cb ? cb(null, id) : that.exitCli(conf.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.getVersion"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>getVersion (cb)](#apidoc.element.pm2.custom.prototype.getVersion)
- description and source-code
```javascript
getVersion = function (cb) {
  var that = this;

  that.Client.executeRemote('getVersion', {}, function(err) {
    return cb ? cb.apply(null, arguments) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.gracefulReload"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>gracefulReload (process_name, opts, cb)](#apidoc.element.pm2.custom.prototype.gracefulReload)
- description and source-code
```javascript
gracefulReload = function (process_name, opts, cb) {
  var that = this;

  if (typeof(opts) == "function") {
    cb = opts;
    opts = {};
  }

  //Common.printOut(conf.PREFIX_MSG_WARNING + chalk.bold.yellow('Warning gracefulReload will be soon deprecated'));
  //Common.printOut(conf.PREFIX_MSG_WARNING + chalk.bold.yellow('Use http://pm2.keymetrics.io/docs/usage/signals-clean-restart/
instead'));

  if (Common.isConfigFile(process_name))
    that._startJson(process_name, commander, 'softReloadProcessId');
  else {
    if (opts && !opts.updateEnv)
      Common.printOut(IMMUTABLE_MSG);
    that._operate('softReloadProcessId', process_name, opts, cb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.install"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>install (module_name, cb)](#apidoc.element.pm2.custom.prototype.install)
- description and source-code
```javascript
install = function (module_name, cb) {
  var that = this;

  Modularizer.install(this, module_name, function(err, data) {
    if (err) {
      Common.printError(cst.PREFIX_MSG_ERR + (err.message || err));
      return cb ? cb(Common.retErr(err)) : that.speedList(cst.ERROR_EXIT);
    }

    // Check if special module with post_install display
    if (data && data[0] && data[0].pm2_env && data[0].pm2_env.PM2_EXTRA_DISPLAY) {
      return postDisplay.call(that, data[0].pm2_env, cb);
    }
    return cb ? cb(null, data) : that.speedList(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.interact"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>interact (secret_key, public_key, machine_name, cb)](#apidoc.element.pm2.custom.prototype.interact)
- description and source-code
```javascript
interact = function (secret_key, public_key, machine_name, cb) {
  var that = this;

  KMDaemon.launchAndInteract(that._conf, {
    secret_key   : secret_key || null,
    public_key   : public_key || null,
    machine_name : machine_name || null
  }, function(err, dt) {
    if (err) {
      return cb ? cb(err) : that.exitCli(cst.ERROR_EXIT);
    }
    return cb ? cb(null, dt) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.interactInfos"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>interactInfos (cb)](#apidoc.element.pm2.custom.prototype.interactInfos)
- description and source-code
```javascript
interactInfos = function (cb) {
  KMDaemon.getInteractInfo(this._conf, function(err, data) {
    if (err)
      return cb(Common.retErr(err));
    return cb(null, data);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.jlist"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>jlist (debug)](#apidoc.element.pm2.custom.prototype.jlist)
- description and source-code
```javascript
jlist = function (debug) {
  var that = this;

  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError(err);
      that.exitCli(conf.ERROR_EXIT);
    }

    if (debug) {
      process.stdout.write(util.inspect(list, false, null, false));
    }
    else {
      process.stdout.write(JSON.stringify(list));
    }

    that.exitCli(conf.SUCCESS_EXIT);

  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.kill"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>kill (cb)](#apidoc.element.pm2.custom.prototype.kill)
- description and source-code
```javascript
kill = function (cb) {
  var that = this;

  var semver = require('semver');
  Common.printOut(conf.PREFIX_MSG + 'Stopping PM2...');

  that.Client.executeRemote('notifyKillPM2', {}, function() {});

  that.getVersion(function(err, data) {
    if (!err && semver.lt(data, '1.1.0')) {
      // Disable action command output if upgrading from < 1.1.0 PM2
      // This is in order to avoid duplicated output
      process.env.PM2_SILENT = 'true';
      console.log(conf.PREFIX_MSG + 'Killing processes...');
    }

    that.killAllModules(function() {
      that._operate('deleteProcessId', 'all', function(err, list) {
        Common.printOut(conf.PREFIX_MSG + 'All processes have been stopped and deleted');
        process.env.PM2_SILENT = 'false';

        that.killInteract(function(err, data) {
          that.Client.killDaemon(function(err, res) {
            if (err) Common.printError(err);
            Common.printOut(conf.PREFIX_MSG + 'PM2 stopped');
            return cb ? cb(err, res) : that.exitCli(conf.SUCCESS_EXIT);
          });
        });
      });
    });

  });
}
```
- example usage
```shell
...
    console.log('RPC closed');
    that.pub_socket.close(function() {
console.log('PUB closed');

// notify cli that the daemon is shuting down (only under unix since windows doesnt handle signals)
if (cst.IS_WINDOWS === false) {
  try {
    process.kill(parseInt(opts.pid), 'SIGQUIT');
  } catch(e) {
    console.error('Could not send SIGQUIT to CLI');
  }
}

console.log('PM2 successfully stopped');
setTimeout(function() {
...
```

#### <a name="apidoc.element.pm2.custom.prototype.killAllModules"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>killAllModules (cb)](#apidoc.element.pm2.custom.prototype.killAllModules)
- description and source-code
```javascript
killAllModules = function (cb) {
  var that = this;

  this.Client.getAllModulesId(function(err, modules_id) {
    async.forEachLimit(modules_id, 1, function(id, next) {
      that._operate('deleteProcessId', id, next);
    }, function() {
      return cb ? cb() : false;
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.killDaemon"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>killDaemon (cb)](#apidoc.element.pm2.custom.prototype.killDaemon)
- description and source-code
```javascript
killDaemon = function (cb) {
  var that = this;

  var semver = require('semver');
  Common.printOut(conf.PREFIX_MSG + 'Stopping PM2...');

  that.Client.executeRemote('notifyKillPM2', {}, function() {});

  that.getVersion(function(err, data) {
    if (!err && semver.lt(data, '1.1.0')) {
      // Disable action command output if upgrading from < 1.1.0 PM2
      // This is in order to avoid duplicated output
      process.env.PM2_SILENT = 'true';
      console.log(conf.PREFIX_MSG + 'Killing processes...');
    }

    that.killAllModules(function() {
      that._operate('deleteProcessId', 'all', function(err, list) {
        Common.printOut(conf.PREFIX_MSG + 'All processes have been stopped and deleted');
        process.env.PM2_SILENT = 'false';

        that.killInteract(function(err, data) {
          that.Client.killDaemon(function(err, res) {
            if (err) Common.printError(err);
            Common.printOut(conf.PREFIX_MSG + 'PM2 stopped');
            return cb ? cb(err, res) : that.exitCli(conf.SUCCESS_EXIT);
          });
        });
      });
    });

  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.killInteract"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>killInteract (cb)](#apidoc.element.pm2.custom.prototype.killInteract)
- description and source-code
```javascript
killInteract = function (cb) {
  var that = this;
  KMDaemon.killInteractorDaemon(that._conf, function(err) {
    return cb ? cb(Common.retErr('Interactor not launched')) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.launchBus"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>launchBus (cb)](#apidoc.element.pm2.custom.prototype.launchBus)
- description and source-code
```javascript
launchBus = function (cb) {
  this.Client.launchBus(cb);
}
```
- example usage
```shell
...
fmt.field('Watch and Restart', chalk.green('Enabled'));
fmt.field('Ignored folder', opts.ignore_watch || 'node_modules');
if (opts.postExec)
  fmt.field('Post restart cmd', opts.postExec);
fmt.sep();

setTimeout(function() {
  pm2.Client.launchBus(function(err, bus) {
    bus.on('process:event', function(packet) {
      if (packet.event == 'online') {
        if (opts.postExec)
          postExecCmd(opts.postExec);
      }
    });
  });
...
```

#### <a name="apidoc.element.pm2.custom.prototype.launchModules"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>launchModules (cb)](#apidoc.element.pm2.custom.prototype.launchModules)
- description and source-code
```javascript
launchModules = function (cb) {
  Modularizer.launchAll(this, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.list"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>list (opts, cb)](#apidoc.element.pm2.custom.prototype.list)
- description and source-code
```javascript
list = function (opts, cb) {
  var that = this;

  if (typeof(opts) == 'function') {
    cb = opts;
    opts = null;
  }

  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
    }

    if (opts && opts.rawArgs && opts.rawArgs.indexOf('--watch') > -1) {
      var moment = require('moment');
      function show() {
        process.stdout.write('\033[2J');
        process.stdout.write('\033[0f');
        console.log('Last refresh: ', moment().format('LTS'));
        that.Client.executeRemote('getMonitorData', {}, function(err, list) {
          UX.dispAsTable(list, null);
        });
      }

      show();
      setInterval(show, 900);
      return false;
    }

    return cb ? cb(null, list) : that.speedList();
  });
}
```
- example usage
```shell
...
  }
  else
    process.exit(0);
}

function autoExit(final) {
  setTimeout(function() {
    pm2.list(function(err, apps) {
if (err) console.error(err.stack || err);

var online_count = 0;

apps.forEach(function(app) {
  if (app.pm2_env.status == cst.ONLINE_STATUS ||
      app.pm2_env.status == cst.LAUNCHING_STATUS)
...
```

#### <a name="apidoc.element.pm2.custom.prototype.logrotate"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>logrotate (opts, cb)](#apidoc.element.pm2.custom.prototype.logrotate)
- description and source-code
```javascript
logrotate = function (opts, cb) {
  var that = this;

  if (process.getuid() != 0) {
    return exec('whoami', function(err, stdout, stderr) {
      Common.printError(cst.PREFIX_MSG + 'You have to run this command as root. Execute the following command:');
      Common.printError(cst.PREFIX_MSG + chalk.grey('      sudo env PATH=$PATH:' + path.dirname(process.execPath) + ' pm2 logrotate
 -u ' + stdout.trim()));

      cb ? cb(Common.retErr('You have to run this with elevated rights')) : that.exitCli(cst.ERROR_EXIT);
    });
  }

  if (!fs.existsSync('/etc/logrotate.d')) {
    Common.printError(cst.PREFIX_MSG + '/etc/logrotate.d does not exist we can not copy the default configuration.');
    return cb ? cb(Common.retErr('/etc/logrotate.d does not exist')) : that.exitCli(cst.ERROR_EXIT);
  }

  var templatePath = path.join(cst.TEMPLATE_FOLDER, cst.LOGROTATE_SCRIPT);
  Common.printOut(cst.PREFIX_MSG + 'Getting logrorate template ' + templatePath);
  var script = fs.readFileSync(templatePath, {encoding: 'utf8'});

  var user = opts.user || 'root';

  script = script.replace(/%HOME_PATH%/g, cst.PM2_ROOT_PATH)
    .replace(/%USER%/g, user);

  try {
    fs.writeFileSync('/etc/logrotate.d/pm2-'+user, script);
  } catch (e) {
    console.error(e.stack || e);
  }

  Common.printOut(cst.PREFIX_MSG + 'Logrotate configuration added to /etc/logrotate.d/pm2');
  return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.monit"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>monit (cb)](#apidoc.element.pm2.custom.prototype.monit)
- description and source-code
```javascript
monit = function (cb) {
  var that = this;

  var Monit = require('./Monit.js');

  if (cb) return cb(new Error('Monit cant be called programmatically'));

  Monit.init();

  function launchMonitor() {
    that.Client.executeRemote('getMonitorData', {}, function(err, list) {
      if (err) {
        console.error('Error retrieving process list: ' + err);
        that.exitCli(conf.ERROR_EXIT);
      }

      Monit.refresh(list);

      setTimeout(function() {
        launchMonitor();
      }, 400);
    });
  }

  launchMonitor();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.msgProcess"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>msgProcess (opts, cb)](#apidoc.element.pm2.custom.prototype.msgProcess)
- description and source-code
```javascript
msgProcess = function (opts, cb) {
  var that = this;

  that.Client.executeRemote('msgProcess', opts, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.multiset"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>multiset (serial, cb)](#apidoc.element.pm2.custom.prototype.multiset)
- description and source-code
```javascript
multiset = function (serial, cb) {
  var that = this;

  Configuration.multiset(serial, function(err, data) {
    if (err)
      return cb ? cb({success:false, err:err}) : that.exitCli(cst.ERROR_EXIT);

    var values = [];
    var key = serial.match(/(?:[^ "]+|"[^"]*")+/g)[0];

    if (key.indexOf('.') > -1)
      values = key.split('.');

    if (key.indexOf(':') > -1)
      values = key.split(':');

    if (values && values.length > 1) {
      // The first element is the app name (module_conf.json)
      var app_name = values[0];

      process.env.PM2_PROGRAMMATIC = 'true';
      that.restart(app_name, {
        updateEnv : true
      }, function(err, data) {
        process.env.PM2_PROGRAMMATIC = 'false';
        if (!err)
          Common.printOut(cst.PREFIX_MSG + 'Module %s restarted', app_name);
        displayConf(app_name, function() {
          return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
        });
      });
      return false;
    }
    displayConf(app_name, function() {
      return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
    });

  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.ping"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>ping (cb)](#apidoc.element.pm2.custom.prototype.ping)
- description and source-code
```javascript
ping = function (cb) {
  var that = this;

  that.Client.executeRemote('ping', {}, function(err, res) {
    if (err) {
      Common.printError(err);
      return cb ? cb(new Error(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    Common.printOut(res);
    return cb ? cb(null, res) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.printLogs"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>printLogs (id, lines, raw, timestamp, exclusive)](#apidoc.element.pm2.custom.prototype.printLogs)
- description and source-code
```javascript
printLogs = function (id, lines, raw, timestamp, exclusive) {
  var that = this;
  var files_list = [];

  // If no argument is given, we stream logs for all running apps
  id = id || 'all';
  lines = lines !== undefined ? lines : 20;
  lines = lines < 0 ? -(lines) : lines;

  // Avoid duplicates and check if path is different from '/dev/null'
  var pushIfUnique = function(entry) {
    var exists = false;

    if (entry.path.toLowerCase
        && entry.path.toLowerCase() !== '/dev/null') {

      files_list.some(function(file) {
        if (file.path === entry.path)
          exists = true;
        return exists;
      });

      if (exists)
        return;

      files_list.push(entry);
    }
  }

  // Get the list of all running apps
  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError(err);
      that.exitCli(cst.ERROR_EXIT);
    }

    if (lines <= 0) {
      return that.exitCli(cst.SUCCESS_EXIT)
    }

    Common.printOut(chalk.bold.grey(util.format.call(this, '[TAILING] Tailing last %d lines for [%s] process%s (change the value
 with --lines option)', lines, id, id === 'all' ? 'es' : '')));

    // Populate the array 'files_list' with the paths of all files we need to tail
    list.forEach(function(proc) {
      if (proc.pm2_env && (id === 'all' ||
                           proc.pm2_env.name == id ||
                           proc.pm2_env.pm_id == id)) {
        if (proc.pm2_env.pm_out_log_path && exclusive !== 'err')
          pushIfUnique({
            path     : proc.pm2_env.pm_out_log_path,
            app_name :proc.pm2_env.pm_id + '|' + proc.pm2_env.name,
            type     : 'out'});
        if (proc.pm2_env.pm_err_log_path && exclusive !== 'out')
          pushIfUnique({
            path     : proc.pm2_env.pm_err_log_path,
            app_name : proc.pm2_env.pm_id + '|' + proc.pm2_env.name,
            type     : 'err'
          });
      }
    });

    if (!raw && (id === 'all' || id === 'PM2') && exclusive === false) {
      Log.tail([{
        path     : cst.PM2_LOG_FILE_PATH,
        app_name : 'PM2',
        type     : 'PM2'
      }], lines, raw, function() {
        Log.tail(files_list, lines, raw, function() {
          that.exitCli(cst.SUCCESS_EXIT);
        });
      });
    }
    else {
      Log.tail(files_list, lines, raw, function() {
        that.exitCli(cst.SUCCESS_EXIT);
      });
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.profilePM2"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>profilePM2 (command, cb)](#apidoc.element.pm2.custom.prototype.profilePM2)
- description and source-code
```javascript
profilePM2 = function (command, cb) {
  var that = this;
  var moment = require('moment');
  var file = path.join(process.cwd(), moment().format('dd-HH:mm:ss') + '.cpuprofile');

  if (command == 'start') {
    that.Client.executeRemote('profileStart', {
    }, function(err) {
      if (err) {
        console.error(err);
        return that.exitCli(1);
      }
      console.log('CPU profiling started, type pm2 profile stop once finished');
      return cb ? cb.apply(null, arguments) : that.exitCli(cst.SUCCESS_EXIT);
    });
  }
  else if (command == 'stop') {
    that.Client.executeRemote('profileStop', {
      pwd : file
    }, function(err) {
      if (err) {
        console.error(err);
        return that.exitCli(1);
      }
      console.log('CPU profile in %s', file);
      return cb ? cb.apply(null, arguments) : that.exitCli(cst.SUCCESS_EXIT);
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.publish"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>publish (module_name, cb)](#apidoc.element.pm2.custom.prototype.publish)
- description and source-code
```javascript
publish = function (module_name, cb) {
  var that = this;

  Modularizer.publish(function(err, data) {
    if (err)
      return cb ? cb(Common.retErr(err)) : that.speedList(cst.ERROR_EXIT);
    return cb ? cb(null, data) : that.speedList(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.pullAndGracefulReload"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullAndGracefulReload (process_name, cb)](#apidoc.element.pm2.custom.prototype.pullAndGracefulReload)
- description and source-code
```javascript
pullAndGracefulReload = function (process_name, cb) {
  this._pull({process_name: process_name, action: 'gracefulReload'}, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.pullAndReload"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullAndReload (process_name, cb)](#apidoc.element.pm2.custom.prototype.pullAndReload)
- description and source-code
```javascript
pullAndReload = function (process_name, cb) {
  this._pull({process_name: process_name, action: 'reload'}, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.pullAndRestart"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullAndRestart (process_name, cb)](#apidoc.element.pm2.custom.prototype.pullAndRestart)
- description and source-code
```javascript
pullAndRestart = function (process_name, cb) {
  this._pull({process_name: process_name, action: 'reload'}, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.pullCommitId"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>pullCommitId (process_name, commit_id, cb)](#apidoc.element.pm2.custom.prototype.pullCommitId)
- description and source-code
```javascript
pullCommitId = function (process_name, commit_id, cb) {
  var reload_type = 'reload';
  var that = this;

  printOut(cst.PREFIX_MSG + 'Updating repository for process name %s', process_name);

  that.Client.getProcessByName(process_name, function(err, processes) {

    if (processes.length === 0) {
      printError('No processes with this name: %s', process_name);
      return cb ? cb({msg:'Process not found: ' + process_name}) : that.exitCli(cst.ERROR_EXIT);
    }

    var proc = processes[0];
    if (proc.pm2_env.versioning) {
      vizion.isUpToDate({folder: proc.pm2_env.versioning.repo_path}, function(err, meta) {
        if (err !== null)
          return cb ? cb({msg:err}) : that.exitCli(cst.ERROR_EXIT);
        vizion.revertTo(
          {revision: commit_id,
           folder: proc.pm2_env.versioning.repo_path},
          function(err2, meta2) {
            if (!err2 && meta2.success) {
              getPostUpdateCmds(proc.pm2_env.versioning.repo_path, process_name, function (command_list) {
                execCommands(proc.pm2_env.versioning.repo_path, command_list, function(err, res) {
                  if (err !== null)
                  {
                    printError(err);
                    return cb ? cb({msg:err}) : that.exitCli(cst.ERROR_EXIT);
                  }
                  else {
                    printOut(cst.PREFIX_MSG + 'Process successfully updated %s', process_name);
                    printOut(cst.PREFIX_MSG + 'Current commit %s', commit_id);
                    return that[reload_type](process_name, cb);
                  }
                });
              });
            }
            else {
              printOut(cst.PREFIX_MSG + 'Already up-to-date or an error occured: %s', process_name);
              return cb ? cb(null, {success:meta.success}) : that.exitCli(cst.SUCCESS_EXIT);
            }
          });
      });
    }
    else {
      printOut(cst.PREFIX_MSG + 'No versioning system found for process %s', process_name);
      return cb ? cb(null, {success:false}) : that.exitCli(cst.SUCCESS_EXIT);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.reload"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>reload (process_name, opts, cb)](#apidoc.element.pm2.custom.prototype.reload)
- description and source-code
```javascript
reload = function (process_name, opts, cb) {
  var that = this;

  if (typeof(opts) == "function") {
    cb = opts;
    opts = {};
  }

  if (Common.isConfigFile(process_name))
    that._startJson(process_name, opts, 'reloadProcessId');
  else {
    if (opts && !opts.updateEnv)
      Common.printOut(IMMUTABLE_MSG);
    that._operate('reloadProcessId', process_name, opts, cb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.reloadLogs"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>reloadLogs (cb)](#apidoc.element.pm2.custom.prototype.reloadLogs)
- description and source-code
```javascript
reloadLogs = function (cb) {
  var that = this;

  Common.printOut('Reloading all logs...');
  that.Client.executeRemote('reloadLogs', {}, function(err, logs) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    Common.printOut('All logs reloaded');
    return cb ? cb(null, logs) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
...
var that = this;

process.on('SIGTERM', that.gracefullExit);
process.on('SIGINT', that.gracefullExit);
process.on('SIGHUP', function() {});
process.on('SIGQUIT', that.gracefullExit);
process.on('SIGUSR2', function() {
  God.reloadLogs({}, function() {});
});
}

Daemon.prototype.sendReady = function(cb) {
// Send ready message to Client
if (this.rpc_socket_ready == true && this.pub_socket_ready == true) {
  cb(null, {
...
```

#### <a name="apidoc.element.pm2.custom.prototype.remote"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>remote (command, opts, cb)](#apidoc.element.pm2.custom.prototype.remote)
- description and source-code
```javascript
remote = function (command, opts, cb) {
  var that = this;

  that[command](opts.name, function(err_cmd, ret) {
    if (err_cmd)
      console.error(err_cmd);
    console.log('Command %s finished', command);
    return cb(err_cmd, ret);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.remoteV2"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>remoteV2 (command, opts, cb)](#apidoc.element.pm2.custom.prototype.remoteV2)
- description and source-code
```javascript
remoteV2 = function (command, opts, cb) {
  var that = this;

  if (that[command].length == 1)
    return that[command](cb);

  opts.args.push(cb);
  return that[command].apply(this, opts.args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.reset"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>reset (process_name, cb)](#apidoc.element.pm2.custom.prototype.reset)
- description and source-code
```javascript
reset = function (process_name, cb) {
  var that = this;

  function processIds(ids, cb) {
    async.eachLimit(ids, conf.CONCURRENT_ACTIONS, function(id, next) {
      that.Client.executeRemote('resetMetaProcessId', id, function(err, res) {
        if (err) console.error(err);
        Common.printOut(conf.PREFIX_MSG + 'Resetting meta for process id %d', id);
        return next();
      });
    }, function(err) {
      if (err) return cb(Common.retErr(err));
      return cb ? cb(null, {success:true}) : that.speedList();
    });
  }

  if (process_name == 'all') {
    that.Client.getAllProcessId(function(err, ids) {
      if (err) {
        Common.printError(err);
        return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
      }
      return processIds(ids, cb);
    });
  }
  else if (isNaN(process_name)) {
    that.Client.getProcessIdByName(process_name, function(err, ids) {
      if (err) {
        Common.printError(err);
        return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
      }
      if (ids.length === 0) {
        Common.printError('Unknown process name');
        return cb ? cb(new Error('Unknown process name')) : that.exitCli(conf.ERROR_EXIT);
      }
      return processIds(ids, cb);
    });
  } else {
    processIds([process_name], cb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.restart"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>restart (cmd, opts, cb)](#apidoc.element.pm2.custom.prototype.restart)
- description and source-code
```javascript
restart = function (cmd, opts, cb) {
  if (typeof(opts) == "function") {
    cb = opts;
    opts = {};
  }
  var that = this;

  if (typeof(cmd) === 'number')
    cmd = cmd.toString();

  if (cmd == "-") {
    // Restart from PIPED JSON
    process.stdin.resume();
    process.stdin.setEncoding('utf8');
    process.stdin.on('data', function (param) {
      process.stdin.pause();
      that.actionFromJson('restartProcessId', param, opts, 'pipe', cb);
    });
  }
  else if (Common.isConfigFile(cmd) || typeof(cmd) === 'object')
    that._startJson(cmd, opts, 'restartProcessId', cb);
  else {
    if (opts && !opts.updateEnv)
      Common.printOut(IMMUTABLE_MSG);
    that._operate('restartProcessId', cmd, opts, cb);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.resurrect"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>resurrect (cb)](#apidoc.element.pm2.custom.prototype.resurrect)
- description and source-code
```javascript
resurrect = function (cb) {
  var apps = {};
  var that = this;

  Common.printOut(cst.PREFIX_MSG + 'Restoring processes located in %s', cst.DUMP_FILE_PATH);

  try {
    apps = fs.readFileSync(cst.DUMP_FILE_PATH);
  } catch(e) {
    Common.printError(cst.PREFIX_MSG_ERR + 'No processes saved; DUMP file doesn\'t exist');
    // if (cb) return cb(Common.retErr(e));
    // else return that.exitCli(cst.ERROR_EXIT);
    return that.speedList();
  }

  var processes = Common.parseConfig(apps, 'none');

  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError(err);
      return that.exitCli(1);
    }

    var current = [];
    var target = [];

    list.forEach(function(app) {
      if (!current[app.name])
        current[app.name] = 0;
      current[app.name]++;
    });

    processes.forEach(function(app) {
      if (!target[app.name])
        target[app.name] = 0;
      target[app.name]++;
    });

    var tostart = Object.keys(target).filter(function(i) {
      return Object.keys(current).indexOf(i) < 0;
    })

    async.eachLimit(processes, cst.CONCURRENT_ACTIONS, function(app, next) {
      if (tostart.indexOf(app.name) == -1)
        return next();
      that.Client.executeRemote('prepare', app, function(err, dt) {
        if (err)
          Common.printError(err);
        else
          Common.printOut(cst.PREFIX_MSG + 'Process %s restored', app.pm_exec_path);
        next();
      });
    }, function(err) {
      return cb ? cb(null, apps) : that.speedList();
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.scale"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>scale (app_name, number, cb)](#apidoc.element.pm2.custom.prototype.scale)
- description and source-code
```javascript
scale = function (app_name, number, cb) {
  var that = this;

  function addProcs(proc, value, cb) {
    (function ex(proc, number) {
      if (number-- === 0) return cb();
      Common.printOut(conf.PREFIX_MSG + 'Scaling up application');
      that.Client.executeRemote('duplicateProcessId', proc.pm2_env.pm_id, ex.bind(this, proc, number));
    })(proc, number);
  }

  function rmProcs(procs, value, cb) {
    var i = 0;

    (function ex(procs, number) {
      if (number++ === 0) return cb();
      that._operate('deleteProcessId', procs[i++].pm2_env.pm_id, ex.bind(this, procs, number));
    })(procs, number);
  }

  function end() {
    return cb ? cb(null, {success:true}) : that.speedList();
  }

  this.Client.getProcessByName(app_name, function(err, procs) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(conf.ERROR_EXIT);
    }

    if (!procs || procs.length === 0) {
      Common.printError(conf.PREFIX_MSG_ERR + 'Application %s not found', app_name);
      return cb ? cb(new Error('App not found')) : that.exitCli(conf.ERROR_EXIT);
    }

    if (procs[0].pm2_env.exec_mode !== 'cluster_mode') {
      Common.printError(conf.PREFIX_MSG_ERR + 'Application %s is not in cluster mode', app_name);
      return cb ? cb(new Error('App not in cluster mode')) : that.exitCli(conf.ERROR_EXIT);
    }

    var proc_number = procs.length;

    if (typeof(number) === 'string' && number.indexOf('+') >= 0) {
      number = parseInt(number, 10);
      return addProcs(procs[0], number, end);
    }
    else if (typeof(number) === 'string' && number.indexOf('-') >= 0) {
      number = parseInt(number, 10);
      return rmProcs(procs[0], number, end);
    }
    else {
      number = parseInt(number, 10);
      number = number - proc_number;

      if (number < 0)
        return rmProcs(procs, number, end);
      else if (number > 0)
        return addProcs(procs[0], number, end);
      else {
        Common.printError(conf.PREFIX_MSG_ERR + 'Nothing to do');
        return cb ? cb(new Error('Same process number')) : that.exitCli(conf.ERROR_EXIT);
      }
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.sendDataToProcessId"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>sendDataToProcessId (proc_id, packet, cb)](#apidoc.element.pm2.custom.prototype.sendDataToProcessId)
- description and source-code
```javascript
sendDataToProcessId = function (proc_id, packet, cb) {
  var that = this;

  packet.id = proc_id;

  that.Client.executeRemote('sendDataToProcessId', packet, function(err, res) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    Common.printOut('successfully sent data to process');
    return cb ? cb(null, res) : that.speedList();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.sendSignalToProcessId"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>sendSignalToProcessId (signal, process_id, cb)](#apidoc.element.pm2.custom.prototype.sendSignalToProcessId)
- description and source-code
```javascript
sendSignalToProcessId = function (signal, process_id, cb) {
  var that = this;

  that.Client.executeRemote('sendSignalToProcessId', {
    signal : signal,
    process_id : process_id
  }, function(err, list) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    Common.printOut('successfully sent signal %s to process id %s', signal, process_id);
    return cb ? cb(null, list) : that.speedList();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.sendSignalToProcessName"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>sendSignalToProcessName (signal, process_name, cb)](#apidoc.element.pm2.custom.prototype.sendSignalToProcessName)
- description and source-code
```javascript
sendSignalToProcessName = function (signal, process_name, cb) {
  var that = this;

  that.Client.executeRemote('sendSignalToProcessName', {
    signal : signal,
    process_name : process_name
  }, function(err, list) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    Common.printOut('successfully sent signal %s to process name %s', signal, process_name);
    return cb ? cb(null, list) : that.speedList();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.serve"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>serve (target_path, port, opts, cb)](#apidoc.element.pm2.custom.prototype.serve)
- description and source-code
```javascript
serve = function (target_path, port, opts, cb) {
  var that = this;
  var servePort = process.env.PM2_SERVE_PORT || port || 8080;
  var servePath = path.resolve(process.env.PM2_SERVE_PATH || target_path || '.');

  var filepath = path.resolve(path.dirname(module.filename), './Serve.js');

  if (!opts.name || typeof(opts.name) == 'function')
    opts.name = 'static-page-server-' + servePort;
  if (!opts.env)
    opts.env = {};
  opts.env.PM2_SERVE_PORT = servePort;
  opts.env.PM2_SERVE_PATH = servePath;
  opts.cwd = servePath;

  this.start(filepath, opts,  function (err, res) {
    if (err) {
      Common.printError(cst.PREFIX_MSG_ERR + 'Error while trying to serve : ' + err.message || err);
      return cb ? cb(err) : that.speedList(cst.ERROR_EXIT);
    }
    Common.printOut(cst.PREFIX_MSG + 'Serving ' + servePath + ' on port ' + servePort);
    return cb ? cb(null, res) : that.speedList();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.set"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>set (key, value, cb)](#apidoc.element.pm2.custom.prototype.set)
- description and source-code
```javascript
set = function (key, value, cb) {
  var that = this;

<span class="apidocCodeCommentSpan">  /**
   * Specific when setting pm2 password
   * Used for restricted remote actions
   * Also alert Interactor that password has been set
   */
</span>  if (key.indexOf('pm2:passwd') > -1) {
    value = Password.generate(value);
    Configuration.set(key, value, function(err) {
      if (err)
        return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
      InteractorDaemonizer.launchRPC(that._conf, function(err) {
        if (err) {
          displayConf('pm2', function() {
            return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
          });
          return false;
        }
        InteractorDaemonizer.rpc.passwordSet(function() {
          InteractorDaemonizer.disconnectRPC(function() {
            displayConf('pm2', function() {
              return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
            });
          });
        });
        return false;
      });
    });
    return false;
  }

  /**
   * Set value
   */
  Configuration.set(key, value, function(err) {
    if (err)
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);

    var values = [];

    if (key.indexOf('.') > -1)
      values = key.split('.');

    if (key.indexOf(':') > -1)
      values = key.split(':');

    if (values && values.length > 1) {
      // The first element is the app name (module_conf.json)
      var app_name = values[0];

      process.env.PM2_PROGRAMMATIC = 'true';
      that.restart(app_name, {
        updateEnv : true
      }, function(err, data) {
        process.env.PM2_PROGRAMMATIC = 'false';
        if (!err)
          Common.printOut(cst.PREFIX_MSG + 'Module %s restarted', app_name);
        displayConf(app_name, function() {
          return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
        });
      });
      return false;
    }
    displayConf(null, function() {
      return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
    });
  });
}
```
- example usage
```shell
...
var arrays = [];
serial = serial.match(/(?:[^ "]+|"[^"]*")+/g);

while (serial.length > 0)
  arrays.push(serial.splice(0, 2));

async.eachSeries(arrays, function(el, next) {
  Configuration.set(el[0], el[1], next);
}, cb);
};

Configuration.get = function(key, cb) {
Configuration.getAll(function(err, data) {
  var climb = splitKey(key);
...
```

#### <a name="apidoc.element.pm2.custom.prototype.snapshotPM2"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>snapshotPM2 (cb)](#apidoc.element.pm2.custom.prototype.snapshotPM2)
- description and source-code
```javascript
snapshotPM2 = function (cb) {
  var that = this;
  var moment = require('moment');
  var file = path.join(process.cwd(), moment().format('dd-HH:mm:ss') + '.heapsnapshot');

  that.Client.executeRemote('snapshotPM2', {
    pwd : file
  }, function(err) {
    if (err) {
      console.error(err);
      return that.exitCli(1);
    }
    console.log('Heapdump in %s', file);
    return cb ? cb.apply(null, arguments) : that.exitCli(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.speedList"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>speedList (code)](#apidoc.element.pm2.custom.prototype.speedList)
- description and source-code
```javascript
speedList = function (code) {
  var that = this;

  // Do nothing if PM2 called programmatically and not called from CLI (also in exitCli)
  if (conf.PM2_PROGRAMMATIC && process.env.PM2_USAGE != 'CLI') return false;

  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      if (gl_retry == 0) {
        gl_retry += 1;
        return setTimeout(that.speedList.bind(that), 1400);
      }
      console.error('Error retrieving process list: %s.\nA process seems to be on infinite loop, retry in 5 seconds',err);
      return that.exitCli(conf.ERROR_EXIT);
    }
    if (process.stdout.isTTY === false) {
      UX.miniDisplay(list);
    }
    else if (commander.miniList && !commander.silent)
      UX.miniDisplay(list);
    else if (!commander.silent) {
      if (that.gl_interact_infos) {
        Common.printOut(chalk.green.bold('●') + ' Agent Online | Dashboard Access: ' + chalk.bold('https://app.keymetrics.io/#/r
/%s') + ' | Server name: %s', that.gl_interact_infos.public_key, that.gl_interact_infos.machine_name);
      }
      UX.dispAsTable(list, that.gl_interact_infos);
      Common.printOut(chalk.white.italic(' Use 'pm2 show <id|name>' to get more details about an app'));
    }

    if (that.Client.daemon_mode == false) {
      Common.printOut('[--no-daemon] Continue to stream logs');
      Common.printOut('[--no-daemon] Exit on target PM2 exit pid=' + fs.readFileSync(conf.PM2_PID_FILE_PATH).toString());
      global._auto_exit = true;
      return that.streamLogs('all', 0, false, 'HH:mm:ss', false);
    }
    else if (commander.attach === true) {
      return that.streamLogs('all', 0, false, null, false);
    }
    else {
      return that.exitCli(code ? code : conf.SUCCESS_EXIT);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.start"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>start (cmd, opts, cb)](#apidoc.element.pm2.custom.prototype.start)
- description and source-code
```javascript
start = function (cmd, opts, cb) {
  if (typeof(opts) == "function") {
    cb = opts;
    opts = {};
  }
  if (!opts)
    opts = {};

  var that = this;

  if (util.isArray(opts.watch) && opts.watch.length === 0)
    opts.watch = (opts.rawArgs ? !!~opts.rawArgs.indexOf('--watch') : !!~process.argv.indexOf('--watch')) || false;

  if (Common.isConfigFile(cmd) || (typeof(cmd) === 'object'))
    that._startJson(cmd, opts, 'restartProcessId', cb);
  else
    that._startScript(cmd, opts, cb);
}
```
- example usage
```shell
...
}
else if (method.indexOf('restartProcessId') !== -1 && process.argv.indexOf('--watch') > -1) {
  delete app_conf.env.current_conf.watch;
  this.toggleWatch(method, app_conf);
}

if (!this.client || !this.client.call) {
  this.start(function(error) {
    if (error) {
      if (fn)
        return fn(error);
      console.error(error);
      return process.exit(0);
    }
    return self.client.call(method, app_conf, fn);
...
```

#### <a name="apidoc.element.pm2.custom.prototype.startup"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>startup (platform, opts, cb)](#apidoc.element.pm2.custom.prototype.startup)
- description and source-code
```javascript
startup = function (platform, opts, cb) {
  var that = this;
  var actual_platform = detectInitSystem();
  var user = (opts.user || process.env.USER);
  var service_name = 'pm2-' + user;
  var launchd_service_name = 'pm2.' + user;

  if (!platform)
    platform = actual_platform;
  else if (actual_platform && actual_platform !== platform) {
    console.log('-----------------------------------------------------------')
    console.log(' PM2 detected ' + actual_platform + ' but you precised ' + platform)
    console.log(' Please verify that your choice is indeed your init system')
    console.log(' If you arent sure, just run : pm2 startup')
    console.log('-----------------------------------------------------------')
  }
  if (platform == null)
    throw new Error('Init system not found');

  if (!cb) {
    cb = function(err, data) {
      if (err)
        return that.exitCli(cst.ERROR_EXIT);
      return that.exitCli(cst.SUCCESS_EXIT);
    }
  }

  if (process.getuid() != 0) {
    return isNotRoot(platform, opts, cb);
  }

  var destination;
  var commands;
  var template;

  function getTemplate(type) {
    return fs.readFileSync(path.join(__dirname, '..', 'templates/init-scripts', type + '.tpl'), {encoding: 'utf8'});
  }

  switch(platform) {
  case 'ubuntu':
  case 'centos':
  case 'arch':
  case 'oracle':
  case 'systemd':
    template = getTemplate('systemd');
    destination = '/etc/systemd/system/' + service_name + '.service';
    commands = [
      'chmod +x ' + destination,
      'systemctl enable ' + service_name,
      'systemctl start ' + service_name,
      'systemctl daemon-reload',
      'systemctl status ' + service_name
    ];
    break;
  case 'ubuntu14':
  case 'ubuntu12':
  case 'upstart':
    template = getTemplate('upstart');
    destination = '/etc/init.d/' + service_name;
    commands = [
      'chmod +x ' + destination,
      'mkdir -p /var/lock/subsys',
      'touch /var/lock/subsys/' + service_name,
      'update-rc.d ' + service_name + ' defaults'
    ];
    break;
  case 'systemv':
  case 'amazon':
  case 'centos6':
    template = getTemplate('upstart');
    destination = '/etc/init.d/' + service_name;
    commands = [
      'chmod +x ' + destination,
      'mkdir -p /var/lock/subsys',
      'touch /var/lock/subsys/' + service_name,
      'chkconfig --add ' + service_name,
      'chkconfig ' + service_name + ' on',
      'initctl list'
    ];
    break;
  case 'macos':
  case 'darwin':
  case 'launchd':
    template = getTemplate('launchd');
    destination = path.join(process.env.HOME, 'Library/LaunchAgents/' + launchd_service_name + '.plist');
    commands = [
      'launchctl load -w ' + destination
    ]
    break;
  case 'freebsd':
  case 'rcd':
    template = getTemplate('rcd');
    destination = '/etc/rc.d/' + service_name;
    commands = [
      'chmod +x ' + destination,
      'echo "pm2_enable=YES" >> /etc/rc.conf'
    ];
    break;
  case 'openrc':
    template = getTemplate('openrc');
    destination = '/etc/init.d/' + service_name;
    commands = [
      'chmod +x ' + destination,
	      'rc-update add ' + service_name + ' default'
    ];
    break;
  default:
    throw new Error('Unknown platform / init system name');
  }

<span class="apidocCodeCommentSpan">  /**
   * 4# Replace template variable value
   */
</span>  template = template.replace(/%PM2_PATH%/g, process.mainModule.filename)
    .replace(/%NODE_PATH%/g, path.dirname(process.execPath))
    .replace(/%USER%/g, user)
    .replace(/%HOME_PATH%/g, opts.hp ? path.resolve(opts.hp, '.pm2') : cst.PM2_ROOT_PATH);

  console.log(chalk.bold('Platform'), platform);
  console.log(chalk.bold('Template'));
  console.log(template);
  console.log(chalk.bold('Target path'));
  console.log(destination);
  console.log(chalk.bold('Command list'));
  console.log(commands);

  Common.printOut(cst.PREFIX_MSG + 'Writing init configuration in ' + destination);
  try {
    fs.writeFileSync(destination, template);
  } catch (e) {
    console.error(cst.PREFIX_MSG_ERR + 'Failure when trying to write startup script');
    console.error(e.message || e);
    return cb(e);
  }

  Common.printOut(cst. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.stop"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>stop (process_name, cb)](#apidoc.element.pm2.custom.prototype.stop)
- description and source-code
```javascript
stop = function (process_name, cb) {
  var that = this;

  if (typeof(process_name) === 'number')
    process_name = process_name.toString();

  if (process_name == "-") {
    process.stdin.resume();
    process.stdin.setEncoding('utf8');
    process.stdin.on('data', function (param) {
      process.stdin.pause();
      that.actionFromJson('stopProcessId', param, commander, 'pipe', cb);
    });
  }
  else if (Common.isConfigFile(process_name))
    that.actionFromJson('stopProcessId', process_name, commander, 'file', cb);
  else
    that._operate('stopProcessId', process_name, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.streamLogs"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>streamLogs (id, lines, raw, timestamp, exclusive)](#apidoc.element.pm2.custom.prototype.streamLogs)
- description and source-code
```javascript
streamLogs = function (id, lines, raw, timestamp, exclusive) {
  var that = this;
  var files_list = [];

  // If no argument is given, we stream logs for all running apps
  id = id || 'all';
  lines = lines !== undefined ? lines : 20;
  lines = lines < 0 ? -(lines) : lines;

  // Avoid duplicates and check if path is different from '/dev/null'
  var pushIfUnique = function(entry) {
    var exists = false;

    if (entry.path.toLowerCase
        && entry.path.toLowerCase() !== '/dev/null') {

      files_list.some(function(file) {
        if (file.path === entry.path)
          exists = true;
        return exists;
      });

      if (exists)
        return;

      files_list.push(entry);
    }
  }

  // Get the list of all running apps
  that.Client.executeRemote('getMonitorData', {}, function(err, list) {
    if (err) {
      Common.printError(err);
      that.exitCli(cst.ERROR_EXIT);
    }

    if (lines === 0 || raw)
      return Log.stream(that.Client, id, raw, timestamp, exclusive);

    Common.printOut(chalk.bold.grey(util.format.call(this, '[TAILING] Tailing last %d lines for [%s] process%s (change the value
 with --lines option)', lines, id, id === 'all' ? 'es' : '')));

    // Populate the array 'files_list' with the paths of all files we need to tail
    list.forEach(function(proc) {
      if (proc.pm2_env && (id === 'all' ||
                           proc.pm2_env.name == id ||
                           proc.pm2_env.pm_id == id)) {
        if (proc.pm2_env.pm_out_log_path && exclusive !== 'err')
          pushIfUnique({
            path     : proc.pm2_env.pm_out_log_path,
            app_name :proc.pm2_env.pm_id + '|' + proc.pm2_env.name,
            type     : 'out'});
        if (proc.pm2_env.pm_err_log_path && exclusive !== 'out')
          pushIfUnique({
            path     : proc.pm2_env.pm_err_log_path,
            app_name : proc.pm2_env.pm_id + '|' + proc.pm2_env.name,
            type     : 'err'
          });
      }
    });

    if (!raw && (id === 'all' || id === 'PM2') && exclusive === false) {
      Log.tail([{
        path     : cst.PM2_LOG_FILE_PATH,
        app_name : 'PM2',
        type     : 'PM2'
      }], lines, raw, function() {
        Log.tail(files_list, lines, raw, function() {
          Log.stream(that.Client, id, raw, timestamp, exclusive);
        });
      });
    }
    else {
      Log.tail(files_list, lines, raw, function() {
        Log.stream(that.Client, id, raw, timestamp, exclusive);
      });
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.trigger"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>trigger (pm_id, action_name, params, cb)](#apidoc.element.pm2.custom.prototype.trigger)
- description and source-code
```javascript
trigger = function (pm_id, action_name, params, cb) {
  if (typeof(params) === 'function') {
    cb = params;
    params = null;
  }
  var cmd = {
    msg : action_name
  };
  var counter = 0;
  var process_wait_count = 0;
  var that = this;
  var results = [];

  if (params)
    cmd.opts = params;
  if (isNaN(pm_id))
    cmd.name = pm_id;
  else
    cmd.id = pm_id;

  this.launchBus(function(err, bus) {
    bus.on('axm:reply', function(ret) {
      if (ret.process.name == pm_id || ret.process.pm_id == pm_id) {
        results.push(ret);
        Common.printOut('[%s:%s]=%j', ret.process.name, ret.process.pm_id, ret.data.return);
        if (++counter == process_wait_count)
          return cb ? cb(null, results) : that.exitCli(cst.SUCCESS_EXIT);
      }
    });
  });

  that.msgProcess(cmd, function(err, data) {
    if (err) {
      Common.printError(err);
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }
    process_wait_count = data.process_count;
    Common.printOut(chalk.bold('%s processes have received command %s'),
                    data.process_count, action_name);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.uninstall"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>uninstall (module_name, cb)](#apidoc.element.pm2.custom.prototype.uninstall)
- description and source-code
```javascript
uninstall = function (module_name, cb) {
  var that = this;

  Modularizer.uninstall(this, module_name, function(err, data) {
    if (err)
      return cb ? cb(Common.retErr(err)) : that.speedList(cst.ERROR_EXIT);
    return cb ? cb(null, data) : that.speedList(cst.SUCCESS_EXIT);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.uninstallStartup"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>uninstallStartup (platform, opts, cb)](#apidoc.element.pm2.custom.prototype.uninstallStartup)
- description and source-code
```javascript
uninstallStartup = function (platform, opts, cb) {
  var commands;
  var that = this;
  var actual_platform = detectInitSystem();
  var user = opts.user || process.env.USER;
  var service_name = 'pm2-' + user;
  var launchd_service_name = 'pm2.' + user;

  if (!platform)
    platform = actual_platform;
  else if (actual_platform && actual_platform !== platform) {
    console.log('-----------------------------------------------------------')
    console.log(' PM2 detected ' + actual_platform + ' but you precised ' + platform)
    console.log(' Please verify that your choice is indeed your init system')
    console.log(' If you arent sure, just run : pm2 startup')
    console.log('-----------------------------------------------------------')
  }
  if (platform === null)
    throw new Error('Init system not found')

  if (!cb) {
    cb = function(err, data) {
      if (err)
        return that.exitCli(cst.ERROR_EXIT);
      return that.exitCli(cst.SUCCESS_EXIT);
    }
  }

  if (process.getuid() != 0) {
    return isNotRoot(platform, opts, cb);
  }

  if (fs.existsSync('/etc/init.d/pm2-init.sh')) {
    platform = 'oldsystem';
  }

  switch(platform) {
  case 'systemd':
    commands = [
      'systemctl stop ' + service_name,
      'systemctl disable ' + service_name,
      'rm /etc/systemd/system/' + service_name + '.service'
    ];
    break;
  case 'systemv':
    commands = [
      'chkconfig ' + service_name + ' off',
      'rm /etc/init.d/' + service_name
    ];
    break;
  case 'oldsystem':
    Common.printOut(cst.PREFIX_MSG + 'Disabling and deleting old startup system');
    commands = [
      'update-rc.d pm2-init.sh disable',
      'update-rc.d -f pm2-init.sh remove',
      'rm /etc/init.d/pm2-init.sh'
    ];
    break;
  case 'openrc':
    commands = [
	      '/etc/init.d/' + service_name + ' stop',
      'rc-update delete ' + service_name + ' default',
      'rm /etc/init.d/' + service_name
    ];
    break;
  case 'upstart':
    commands = [
      'update-rc.d ' + service_name + ' disable',
      'update-rc.d -f ' + service_name + ' remove',
      'rm /etc/init.d/' + service_name
    ];
    break;
  case 'launchd':
    var destination = path.join(process.env.HOME, 'Library/LaunchAgents/' + launchd_service_name + '.plist');
    commands = [
      'launchctl remove com.' + launchd_service_name,
      'rm ' + destination
    ];
  };

  shelljs.exec(commands.join('&& '), function(code, stdout, stderr) {
    console.log(stdout);
    console.log(stderr);
    if (code == 0) {
      Common.printOut(cst.PREFIX_MSG + chalk.bold('Init file disabled.'));
    } else {
      Common.printOut(cst.ERROR_MSG + chalk.bold('Return code : ' + code));
    }

    cb(null, {
      commands : commands,
      platform : platform
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.unset"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>unset (key, cb)](#apidoc.element.pm2.custom.prototype.unset)
- description and source-code
```javascript
unset = function (key, cb) {
  var that = this;

  Configuration.unset(key, function(err) {
    if (err) {
      return cb ? cb(Common.retErr(err)) : that.exitCli(cst.ERROR_EXIT);
    }

    displayConf(function() {
      return cb ? cb(null, {success:true}) : that.exitCli(cst.SUCCESS_EXIT);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.update"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>update (cb)](#apidoc.element.pm2.custom.prototype.update)
- description and source-code
```javascript
update = function (cb) {
  var that = this;

  Common.printOut('Be sure to have the latest version by doing 'npm install pm2@latest -g' before doing this procedure.');

  // Dump PM2 processes
  that.Client.executeRemote('notifyKillPM2', {}, function() {});

  that.dump(function(err) {
    debug('Dumping successfull', err);
    that.killDaemon(function() {
      debug('------------------ Everything killed', arguments);
      that.Client.launchDaemon({interactor:false}, function(err, child) {
        that.Client.launchRPC(function() {
          that.resurrect(function() {
            Common.printOut(chalk.blue.bold('>>>>>>>>>> PM2 updated'));
            Modularizer.launchAll(that, function() {
              KMDaemon.launchAndInteract(that._conf, null, function(err, data, interactor_proc) {
                // Interactor error can be skipped here
                return cb ? cb(null, {success:true}) : that.speedList();
              });
            });
          });
        });
      });
    });
  });

  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pm2.custom.prototype.web"></a>[function <span class="apidocSignatureSpan">pm2.custom.prototype.</span>web (port, cb)](#apidoc.element.pm2.custom.prototype.web)
- description and source-code
```javascript
web = function (port, cb) {
  var that = this;

  if (typeof(port) === 'function') {
    cb = port;
    port = 9615;
  }

  var filepath = path.resolve(path.dirname(module.filename), '../HttpInterface.js');

  that.start({
    script : filepath,
    name : 'pm2-http-interface',
    execMode : 'fork_mode',
    env : {
      PM2_WEB_PORT : port
    }
  }, function(err, proc) {
    if (err) {
      Common.printError(cst.PREFIX_MSG_ERR + 'Error while launching application', err.stack || err);
      return cb ? cb(Common.retErr(err)) : that.speedList();
    }
    Common.printOut(cst.PREFIX_MSG + 'Process launched');
    return cb ? cb(null, proc) : that.speedList();
  });
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
