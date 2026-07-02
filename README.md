# devicectl Help Reference

Generated on 2026-07-01 15:31:50 PDT from `/Applications/Xcode.app/Contents/Developer/usr/bin/devicectl`.

This document contains the top-level `devicectl` help and the help output for every subcommand discovered from each `SUBCOMMANDS:` section.

<a id="index"></a>

## Command Index

- [`devicectl`](#devicectl)
- [`devicectl device`](#devicectl-device)
- [`devicectl diagnose`](#devicectl-diagnose)
- [`devicectl list`](#devicectl-list)
- [`devicectl manage`](#devicectl-manage)
- [`devicectl device appResize`](#devicectl-device-appresize)
- [`devicectl device capture`](#devicectl-device-capture)
- [`devicectl device copy`](#devicectl-device-copy)
- [`devicectl device info`](#devicectl-device-info)
- [`devicectl device install`](#devicectl-device-install)
- [`devicectl device notification`](#devicectl-device-notification)
- [`devicectl device orientation`](#devicectl-device-orientation)
- [`devicectl device pairings`](#devicectl-device-pairings)
- [`devicectl device pasteboard`](#devicectl-device-pasteboard)
- [`devicectl device process`](#devicectl-device-process)
- [`devicectl device profile`](#devicectl-device-profile)
- [`devicectl device reboot`](#devicectl-device-reboot)
- [`devicectl device rename`](#devicectl-device-rename)
- [`devicectl device settings`](#devicectl-device-settings)
- [`devicectl device simulate`](#devicectl-device-simulate)
- [`devicectl device sysdiagnose`](#devicectl-device-sysdiagnose)
- [`devicectl device uninstall`](#devicectl-device-uninstall)
- [`devicectl list audioDevices`](#devicectl-list-audiodevices)
- [`devicectl list devices`](#devicectl-list-devices)
- [`devicectl list plugins`](#devicectl-list-plugins)
- [`devicectl list preferredDDI`](#devicectl-list-preferredddi)
- [`devicectl manage ddis`](#devicectl-manage-ddis)
- [`devicectl manage loggingProfile`](#devicectl-manage-loggingprofile)
- [`devicectl manage pair`](#devicectl-manage-pair)
- [`devicectl manage unpair`](#devicectl-manage-unpair)
- [`devicectl device appResize observe`](#devicectl-device-appresize-observe)
- [`devicectl device appResize set`](#devicectl-device-appresize-set)
- [`devicectl device appResize start`](#devicectl-device-appresize-start)
- [`devicectl device capture screen-record`](#devicectl-device-capture-screen-record)
- [`devicectl device capture screenshot`](#devicectl-device-capture-screenshot)
- [`devicectl device copy to`](#devicectl-device-copy-to)
- [`devicectl device copy from`](#devicectl-device-copy-from)
- [`devicectl device info appIcon`](#devicectl-device-info-appicon)
- [`devicectl device info appResize`](#devicectl-device-info-appresize)
- [`devicectl device info appearance`](#devicectl-device-info-appearance)
- [`devicectl device info apps`](#devicectl-device-info-apps)
- [`devicectl device info audio`](#devicectl-device-info-audio)
- [`devicectl device info authListing`](#devicectl-device-info-authlisting)
- [`devicectl device info ddiServices`](#devicectl-device-info-ddiservices)
- [`devicectl device info details`](#devicectl-device-info-details)
- [`devicectl device info displays`](#devicectl-device-info-displays)
- [`devicectl device info files`](#devicectl-device-info-files)
- [`devicectl device info lockState`](#devicectl-device-info-lockstate)
- [`devicectl device info mountpoint`](#devicectl-device-info-mountpoint)
- [`devicectl device info processes`](#devicectl-device-info-processes)
- [`devicectl device install app`](#devicectl-device-install-app)
- [`devicectl device notification post`](#devicectl-device-notification-post)
- [`devicectl device notification observe`](#devicectl-device-notification-observe)
- [`devicectl device orientation get`](#devicectl-device-orientation-get)
- [`devicectl device orientation rotate`](#devicectl-device-orientation-rotate)
- [`devicectl device orientation set`](#devicectl-device-orientation-set)
- [￼`devicectl device pairings list`￼](#devicectl-device-pairings-list)<!-- {"preview":"true"} -->
- [`devicectl device pairings pair`](#devicectl-device-pairings-pair)
- [`devicectl device pairings set-active`](#devicectl-device-pairings-set-active)
- [`devicectl device pairings unpair`](#devicectl-device-pairings-unpair)
- [`devicectl device pasteboard copy`](#devicectl-device-pasteboard-copy)
- [`devicectl device pasteboard paste`](#devicectl-device-pasteboard-paste)
- [`devicectl device pasteboard info`](#devicectl-device-pasteboard-info)
- [`devicectl device pasteboard monitor`](#devicectl-device-pasteboard-monitor)
- [`devicectl device pasteboard transfer`](#devicectl-device-pasteboard-transfer)
- [`devicectl device pasteboard sync-with-host`](#devicectl-device-pasteboard-sync-with-host)
- [`devicectl device process awaitTermination`](#devicectl-device-process-awaittermination)
- [`devicectl device process launch`](#devicectl-device-process-launch)
- [`devicectl device process openURL`](#devicectl-device-process-openurl)
- [`devicectl device process resume`](#devicectl-device-process-resume)
- [`devicectl device process sendMemoryWarning`](#devicectl-device-process-sendmemorywarning)
- [`devicectl device process signal`](#devicectl-device-process-signal)
- [`devicectl device process suspend`](#devicectl-device-process-suspend)
- [`devicectl device process terminate`](#devicectl-device-process-terminate)
- [`devicectl device profile install`](#devicectl-device-profile-install)
- [`devicectl device profile list`](#devicectl-device-profile-list)
- [`devicectl device profile remove`](#devicectl-device-profile-remove)
- [`devicectl device profile validate`](#devicectl-device-profile-validate)
- [`devicectl device settings appearance`](#devicectl-device-settings-appearance)
- [`devicectl device settings audio`](#devicectl-device-settings-audio)
- [`devicectl device settings biometrics`](#devicectl-device-settings-biometrics)
- [`devicectl device settings reset`](#devicectl-device-settings-reset)
- [`devicectl device simulate biometrics`](#devicectl-device-simulate-biometrics)
- [`devicectl device simulate location`](#devicectl-device-simulate-location)
- [`devicectl device simulate statusBar`](#devicectl-device-simulate-statusbar)
- [`devicectl device uninstall app`](#devicectl-device-uninstall-app)
- [`devicectl manage ddis clean`](#devicectl-manage-ddis-clean)
- [`devicectl manage ddis update`](#devicectl-manage-ddis-update)
- [`devicectl manage loggingProfile register`](#devicectl-manage-loggingprofile-register)
- [`devicectl device pasteboard transfer to`](#devicectl-device-pasteboard-transfer-to)
- [`devicectl device pasteboard transfer from`](#devicectl-device-pasteboard-transfer-from)
- [`devicectl device simulate location clear`](#devicectl-device-simulate-location-clear)
- [`devicectl device simulate location coordinate`](#devicectl-device-simulate-location-coordinate)
- [`devicectl device simulate location list`](#devicectl-device-simulate-location-list)
- [`devicectl device simulate location route`](#devicectl-device-simulate-location-route)
- [`devicectl device simulate location scenario`](#devicectl-device-simulate-location-scenario)
- [`devicectl device simulate statusBar clear`](#devicectl-device-simulate-statusbar-clear)
- [`devicectl device simulate statusBar override`](#devicectl-device-simulate-statusbar-override)
- [`devicectl device simulate statusBar preset`](#devicectl-device-simulate-statusbar-preset)
- [`devicectl device simulate statusBar show`](#devicectl-device-simulate-statusbar-show)

## devicectl

```text
OVERVIEW: Core Device Control: a command-line utility for exercising Core
Device functionality.

devicectl is a Core Device command-line utility that you can use to interact
with devices connected to this host. Automation and integration with other
tools is supported via JSON output captured to a file, which is versioned and
will remain stable across releases. Standard output is meant for human
consumption and is not guaranteed to be stable across releases.

USAGE: devicectl [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  device                  Commands to interact with devices.
  diagnose                Gather diagnostic information for debugging or filing
                          bug reports.
  list                    List things that devicectl knows about.
  manage                  Commands to change state between the system and
                          devices, or between devices themselves.

  See 'devicectl help <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


### devicectl device

```text
OVERVIEW: Commands to interact with devices.

Allows users to interact with devices that CoreDevice is aware of.

USAGE: devicectl device [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  appResize               Manage resizable app sessions.
  capture                 Capture the device's screen.
  copy                    Copy files.
  info                    Commands that provide information about a specific
                          device
  install                 Install content onto a device.
  notification            Post and observe Darwin notifications on a device.
  orientation             Control device orientation.
  pairings                Manage watch and phone pairings.
  pasteboard              Interact with the device pasteboard.
  process                 Interact with processes on devices.
  profile                 Manage profiles on a device.
  reboot                  Reboot a device.
  rename                  Rename a device.
  settings                Customize device settings.
  simulate                Simulate device behaviors.
  sysdiagnose             Gather a sysdiagnose for a device.
  uninstall               Uninstall content from a device.

  See 'devicectl help device <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


### devicectl diagnose

```text
OVERVIEW: Gather diagnostic information for debugging or filing bug reports.

This command gathers diagnostic information from the local system and connected
devices that have a mounted Developer Disk Image (DDI).

By default this command will wait for 3600 seconds before exiting. You can
override this by providing a different --timeout value.

'--json-output -' is not supported; pass '--json-output <path>' instead.

If you are running this command to generate diagnostics for a Feedback
Assistant report, you can provide better logging by installing CoreDevice's
CoreDeviceHostLogging profile (located at
/Library/Developer/PrivateFrameworks/CoreDevice.framework/Resources/CoreDeviceHostLogging.mobileconfig).
To install the profile either double-click on
CoreDeviceHostLogging.mobileconfig in Finder or go to System Settings->Privacy
& Security->Profile and add the profile directly.

USAGE: devicectl diagnose <options>

DEVICE OPTIONS:
  -d, --devices <uuid|ecid|udid|name>
                          The identifiers, ECIDs, UDIDs, or names of the
                          devices. If not specified, all known devices are
                          used. For multiple devices, supply this option
                          multiple times, once for each device.

COMMAND OPTIONS:
  -b, --finder/--no-finder
                          Do not show the resulting archive in Finder upon
                          completion. Default is to show the archive in Finder
                          if the current user is controlling the Aqua console
                          session. (default: --finder)
  -k, --keep-temp-dir     Keep the temporary directory after archiving. Default
                          is to delete the directory once the archive has been
                          created.
  -a, --archive-destination <path>
                          The path for the final ZIP archive. By default the
                          archive is placed at
                          '/tmp/devicectl_diagnose_<timestamp>.zip'. This is
                          ignored if --create-radar is passed in (since no
                          archive is created).
  --archive/--no-archive  Do not create an archive, leave the collected files
                          uncompressed. (default: --archive)
  --include-host-sysdiagnose/--no-include-host-sysdiagnose
                          When running the command, include the host
                          sysdiagnose collection, which may increase
                          diagnostics collection time. (default:
                          --include-host-sysdiagnose)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


### devicectl list

```text
OVERVIEW: List things that devicectl knows about.

This command lists different kinds of things that CoreDevice knows about.

USAGE: devicectl list [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  audioDevices            List the host's audio input and output devices.
  devices                 Lists devices that CoreDevice knows about
  plugins                 List loaded plugin information for devicectl and
                          CoreDeviceService. 
  preferredDDI            List the DDI that CoreDevice will use for a given
                          platform.

  See 'devicectl help list <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


### devicectl manage

```text
OVERVIEW: Commands to change state between the system and devices, or between
devices themselves.

Allows users to prepare devices for use, disconnect existing device
connections, and set up relationships between devices themselves or between
accessories and devices.

USAGE: devicectl manage [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  ddis                    Commands used to manage the set of developer disk
                          images present on the host.
  loggingProfile          Commands used to manage the Core Device logging
                          profile.
  pair                    Pair with a given device.
  unpair                  Unpair a manually paired device.

  See 'devicectl help manage <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device appResize

```text
OVERVIEW: Manage resizable app sessions.

Start and adjust resizable app sessions on a device display. The target display
is automatically discovered by finding a display whose name contains
"Resizable". To query the current session state, use 'devicectl device info
appResize'.

USAGE: devicectl device appResize [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  observe                 Observe the device's resizability state.
  set                     Adjust the geometry of an active resizable app
                          session.
  start                   Start a resizable app session.

  See 'devicectl help device appResize <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device capture

```text
OVERVIEW: Capture the device's screen.

Commands for capturing the device's screen content.

USAGE: devicectl device capture [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  screen-record           Record the device's screen.
  screenshot              Capture a screenshot from the device.

  See 'devicectl help device capture <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device copy

```text
OVERVIEW: Copy files.

This command allows you to copy files to and from a device.

USAGE: devicectl device copy [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  to                      Copy a file or directory to the device.
  from                    Receive a file from the remote device.

  See 'devicectl help device copy <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device info

```text
OVERVIEW: Commands that provide information about a specific device

Provides access to device information like processes, installed roots,
installed files, and other device state.

USAGE: devicectl device info [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  appIcon                 Request app icon generation from this device.
  appResize               Get the current resizable app session state.
  appearance              Get Device UI Appearance Information
  apps                    List apps installed on the device.
  audio                   Get device audio settings
  authListing             Get the device's AuthListing identifiers.
  ddiServices             Get information on the developer disk image services
                          on the device.
  details                 Get information about the current device.
  displays                Get the device's current display information.
  files                   List files on the device.
  lockState               Get the current locked state of the device.
  mountpoint              Get the mount point for the device-specific data
                          folder on the host.
  processes               List currently running processes on the device.

  See 'devicectl help device info <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device install

```text
OVERVIEW: Install content onto a device.

This command allows you to install content onto a device.

USAGE: devicectl device install [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  app                     Installs an app.

  See 'devicectl help device install <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device notification

```text
OVERVIEW: Post and observe Darwin notifications on a device.

USAGE: devicectl device notification [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  post                    Post a Darwin notification to a device.
  observe                 Observe a Darwin notification on a device.

  See 'devicectl help device notification <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device orientation

```text
OVERVIEW: Control device orientation.

Query or set simulated device physical orientation (for devices that supported
it).

USAGE: devicectl device orientation [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  get                     Get Device Orientation
  rotate                  Rotate Device Orientation
  set                     Set Device Orientation

  See 'devicectl help device orientation <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device pairings

```text
OVERVIEW: Manage watch and phone pairings.

This command allows you to manage watch and phone pairings on a device.

USAGE: devicectl device pairings [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  list                    List paired devices.
  pair                    Create a new watch and phone pair.
  set-active              Make the watch and phone pairing active.
  unpair                  Unpair a paired watch and phone.

  See 'devicectl help device pairings <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device pasteboard

```text
OVERVIEW: Interact with the device pasteboard.

Copy, paste, inspect, monitor, and synchronize the pasteboard on a device.

USAGE: devicectl device pasteboard [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  copy                    Copy data to the device pasteboard.
  paste                   Paste device pasteboard contents to stdout.
  info                    Show information about the device pasteboard.
  monitor                 Monitor device pasteboard for changes.
  transfer                Transfer pasteboard contents between host and device.
  sync-with-host          Bidirectional pasteboard sync between host and device.

  See 'devicectl help device pasteboard <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device process

```text
OVERVIEW: Interact with processes on devices.

Allows users to interact with processes on devices that CoreDevice is aware of.

USAGE: devicectl device process [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  awaitTermination        Waits for the termination of a remote process.
  launch                  Launch a remote application.
  openURL                 Open a URL on the device.
  resume                  Resume a process on a device.
  sendMemoryWarning       Sends a memory pressure warning to a process on a
                          device.
  signal                  Send a signal to a process on a device.
  suspend                 Suspend a process on a device.
  terminate               Terminate a process on a device.

  See 'devicectl help device process <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device profile

```text
OVERVIEW: Manage profiles on a device.

This command allows you to install, validate, remove, and list profiles on a
device.

Supported profile types:
  - Provisioning profiles (.mobileprovision): Contain entitlements that allow
apps
    to run and access specific capabilities.
  - Configuration profiles (.mobileconfig): Manage device settings and policies
    including WiFi, VPN, email, certificates, and restrictions.

The profile type is auto-detected from the file extension, or can be specified
explicitly using the --type flag.

USAGE: devicectl device profile [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  install                 Install one or more profiles on a device.
  list                    List profiles installed on a device.
  remove                  Remove one or more profiles from a device.
  validate                Validate one or more profiles without installing them.

  See 'devicectl help device profile <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device reboot

```text
OVERVIEW: Reboot a device.

This command reboots a device.

USAGE: devicectl device reboot --device <uuid|ecid|serial_number|udid|name|dns_name> [--style <style>] [--wait-for-device] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --style <style>         The reboot style to use. Either 'full' or 'userspace'
                          can be requested. By default, a full reboot is
                          performed. (default: full)
  -w, --wait-for-device   Whether the command should wait for the device to
                          become available again after rebooting. This option
                          is supported only for devices which are physically
                          connected to the host.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl device rename

```text
OVERVIEW: Rename a device.

This command changes the user-visible name of a device.

USAGE: devicectl device rename --device <uuid|ecid|serial_number|udid|name|dns_name> --name <name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --name <name>           The new name to assign to the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl device settings

```text
OVERVIEW: Customize device settings.

Allows users to customize various device settings such as appearance, locale,
and other preferences.

USAGE: devicectl device settings [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  appearance              Set device user interface appearance
  audio                   Set device audio settings
  biometrics              Query or control biometric settings.
  reset                   Reset a device’s content and settings.

  See 'devicectl help device settings <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device simulate

```text
OVERVIEW: Simulate device behaviors.

Simulate various device behaviors such as location, network conditions,
sensors, etc.

USAGE: devicectl device simulate [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  biometrics              Simulate biometric authentication events.
  location                Simulate device location.
  statusBar               Simulate device status bar appearance.

  See 'devicectl help device simulate <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl device sysdiagnose

```text
OVERVIEW: Gather a sysdiagnose for a device.

This command gathers a sysdiagnose for the indicated device. If you also want
to gather a sysdiagnose for the host and additional Core Device information,
please use `devicectl diagnose` instead.

'--json-output -' is not supported; pass '--json-output <path>' instead.

USAGE: devicectl device sysdiagnose --device <uuid|ecid|serial_number|udid|name|dns_name> [--destination <destination>] [--gather-full-logs] [--dry-run-only] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --destination <destination>
                          Where to place the device's sysdiagnose. By default
                          the sysdiagnose will be placed in a unique temporary
                          directory.
  --gather-full-logs      When running the command, tell sysdiagnose to gather
                          full logs. Since this can result in significantly
                          larger sysdiagnose files, this is off by default.
  --dry-run-only          When running the command, tell sysdiagnose whether to
                          collect diagnostics. This is used for testing.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl device uninstall

```text
OVERVIEW: Uninstall content from a device.

This command allows you to uninstall content from a device.

USAGE: devicectl device uninstall [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  app                     Uninstalls an app.

  See 'devicectl help device uninstall <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl list audioDevices

```text
OVERVIEW: List the host's audio input and output devices.

Lists the audio devices that CoreAudio reports on the host (this Mac). Hidden
devices and private aggregate devices that macOS creates dynamically are
filtered out.

USAGE: devicectl list audioDevices [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl list devices

```text
OVERVIEW: Lists devices that CoreDevice knows about

USAGE: devicectl list devices [--search <search>] [--filter <filter>] [--sort-by <sort-by>] [--columns <columns> ...] [--hide-default-columns] [--hide-headers] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

FILTERING OPTIONS:
  -s, --search <search>   A plain-text search string used to filter results.
        Performs a case-insensitive substring match across all columns. Rows
        where any column contains the search string are included in the output.
         This searches all possible columns, not just visible ones.

        E.g. `--search iPhone` or `-s mac`

        For advanced filtering with specific fields and operators, use
        `--filter` instead.
  --filter <filter>       An NSPredicate expression used to filter the list of
                          items shown.
        The attribute name can be the column's name from either the table-based
        output or a fully qualified JSON field identifier from the JSON output.

        Common operators: = (equals), CONTAINS, BEGINSWITH, ENDSWITH, AND, OR,
        NOT.

        Examples:
          --filter "Name CONTAINS 'iPhone'"
          --filter "Identifier = '00008101-000A0C123456001E'"
          --filter "hardwareProperties.platform BEGINSWITH 'mac'"
          --filter "Name CONTAINS 'iPad' AND State = 'available'"

        For simple text matching across all columns, use `--search` instead.
  --sort-by <sort-by>     If specified, a key path by which to sort results.
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl list plugins

```text
OVERVIEW: List loaded plugin information for devicectl and CoreDeviceService. 

USAGE: devicectl list plugins [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl list preferredDDI

```text
OVERVIEW: List the DDI that CoreDevice will use for a given platform.

This command allows the user to see what Developer Disk Image (DDI) would be
used for a given platform. If no usable DDI is available, this command will
return the best DDI available, even though it is unusable.

USAGE: devicectl list preferredDDI [--platform <platform>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

COMMAND OPTIONS:
  --platform <platform>   The device platform of the requested DDI.
        If this is not provided, DDIs will be shown for all supported
        platforms. Examples: iOS, watchOS

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl manage ddis

```text
OVERVIEW: Commands used to manage the set of developer disk images present on
the host.

Provides commands to clean out the existing set of developer disk images
present on the host and to update the set of DDIs present on the host (given a
directory of candidate DDIs).

USAGE: devicectl manage ddis [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  clean                   Removes any developer disk images installed on the
                          host.
  update                  Update the DDIs installed on the host.

  See 'devicectl help manage ddis <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl manage loggingProfile

```text
OVERVIEW: Commands used to manage the Core Device logging profile.

Provides commands to activate the Core Device logging profile. The Core Device
logging profile ensures that archives of the system logs on your Mac will
contain additional information that is helpful when filing feedback and bug
reports.

USAGE: devicectl manage loggingProfile [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  register                Registers the Core Device logging profile on your Mac
                          and optionally opens System Settings.

  See 'devicectl help manage loggingProfile <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


#### devicectl manage pair

```text
OVERVIEW: Pair with a given device.

This command attempts to pair with a device discovered by CoreDevice.

USAGE: devicectl manage pair --device <uuid|ecid|serial_number|udid|name|dns_name> [--columns <columns> ...] [--hide-default-columns] [--hide-headers] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

FORMATTING OPTIONS:
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


#### devicectl manage unpair

```text
OVERVIEW: Unpair a manually paired device.

This command unpairs a manually paired device.

USAGE: devicectl manage unpair --device <uuid|ecid|serial_number|udid|name|dns_name> [--columns <columns> ...] [--hide-default-columns] [--hide-headers] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

FORMATTING OPTIONS:
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device appResize observe

```text
OVERVIEW: Observe the device's resizability state.

Continuously monitors whether the device has a foreground application that can
be moved to a resizable display. Prints state updates as they occur (for
example, when the user switches between an app and the home screen, or when a
resizable session starts or ends).

This command runs until interrupted (Ctrl+C).

USAGE: devicectl device appResize observe --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device appResize set

```text
OVERVIEW: Adjust the geometry of an active resizable app session.

Adjusts the preferred size and corner radius of an active resizable app
session. The target display is automatically discovered by finding a display
whose name contains "Resizable".

USAGE: devicectl device appResize set --device <uuid|ecid|serial_number|udid|name|dns_name> --preferred-size <WxH> [--corner-radius <radius>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --preferred-size <WxH>  The preferred size for the resizable app, in the
                          format <width>x<height> (e.g. 800x600).
  --corner-radius <radius>
                          The corner radius to use for resizing. (default: 0.0)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device appResize start

```text
OVERVIEW: Start a resizable app session.

Moves the frontmost apps to a resizable display and starts a resizable app
session. The target display is automatically discovered by finding a display
whose name contains "Resizable".

This command runs until interrupted (Ctrl+C). The session ends when the command
exits. While the session is active, use 'devicectl device appResize set' in
another terminal to adjust the display geometry.

USAGE: devicectl device appResize start --device <uuid|ecid|serial_number|udid|name|dns_name> [--preferred-size <WxH>] [--corner-radius <radius>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --preferred-size <WxH>  The preferred size for the resizable app, in the
                          format <width>x<height> (e.g. 800x600).
  --corner-radius <radius>
                          The corner radius to use for resizing. (default: 0.0)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device capture screen-record

```text
OVERVIEW: Record the device's screen.

Records the device's screen to a video file. By default, the recording runs
until interrupted with Ctrl+C, at which point the video is saved to the
specified destination. Use --duration to automatically stop the recording after
a fixed number of seconds.

Use 'devicectl device info displays' to list available displays and their
unique IDs.

USAGE: devicectl device capture screen-record --device <uuid|ecid|serial_number|udid|name|dns_name> --destination <path> [--display-unique-id <unique-id>] [--codec <codec>] [--mask-policy <policy>] [--duration <seconds>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --destination <path>    The file path where the recording will be saved (must
                          be a .mp4 file).
  --display-unique-id <unique-id>
                          The unique ID of the display to record. If not
                          specified, records the primary display. Use
                          'devicectl device info displays' to see available
                          displays.
  --codec <codec>         The video codec to use for encoding. Supported
                          values: h264, hevc. (default: h264)
  --mask-policy <policy>  The mask policy for device bezels. Supported values:
                          ignored, premultipliedAlpha, black. (default: ignored)
  --duration <seconds>    The duration (in seconds) to record before
                          automatically stopping. If not specified, the
                          recording runs until interrupted with Ctrl+C.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device capture screenshot

```text
OVERVIEW: Capture a screenshot from the device.

Captures a screenshot from the device and saves it as a PNG file to the
specified destination.

Use 'devicectl device info displays' to list available displays and their
unique IDs.

USAGE: devicectl device capture screenshot --device <uuid|ecid|serial_number|udid|name|dns_name> --destination <path> [--display-unique-id <unique-id>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --destination <path>    The file path where the screenshot will be saved
                          (must be a .png file).
  --display-unique-id <unique-id>
                          The unique ID of the display to capture. If not
                          specified, captures the primary display. Use
                          'devicectl device info displays' to see available
                          displays.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device copy to

```text
OVERVIEW: Copy a file or directory to the device.

Copies a file or directory to the device, skipping files that have not been
modified.

USAGE: devicectl device copy to --device <uuid|ecid|serial_number|udid|name|dns_name> --source <source> ... [--destination <destination>] [--user <user>] --domain-type <domain-type> [--domain-identifier <domain-identifier>] [--remove-existing-content <remove-existing-content>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

FILE COPY OPTIONS:
  --source <source>       The path of the item to be transferred to the device.
        This flag can be passed multiple times to provide multiple items to
        transfer.

BASE FILE TRANSFER OPTIONS:
  --destination <destination>
                          The location to which the item should be copied.
  -u, --user <user>       The name of the user we should target. Only relevant
                          for certain domains.
  --domain-type <domain-type>
                          The file service domain. Valid values are: temporary,
                          appDataContainer, appGroupDataContainer,
                          systemCrashLogs. You must specify a valid domain and
                          identifier pair. Certain domains must be accompanied
                          by an identifier that provides additional context.
                          For example, if the domain is an app data container,
                          the identifier is the bundle ID of the app. For
                          temporary directories, the identifier is a unique
                          client-provided string which is used to get your own
                          space, separate from those of other clients.
  --domain-identifier <domain-identifier>
                          A unique string used to provide additional context to
                          the domain.
  -r, --remove-existing-content <remove-existing-content>
                          Whether to remove files from the destination
                          directory on the device. Only used when transferring
                          directories. (default: false)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device copy from

```text
OVERVIEW: Receive a file from the remote device.

Copies data from the device, providing domain-specific information (see
arguments below for more information).

USAGE: devicectl device copy from --device <uuid|ecid|serial_number|udid|name|dns_name> --source <source> [--destination <destination>] [--user <user>] --domain-type <domain-type> [--domain-identifier <domain-identifier>] [--remove-existing-content <remove-existing-content>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

FILE RECEIVE OPTIONS:
  --source <source>       The item which should be received.

BASE FILE TRANSFER OPTIONS:
  --destination <destination>
                          The location to which the item should be copied.
  -u, --user <user>       The name of the user we should target. Only relevant
                          for certain domains.
  --domain-type <domain-type>
                          The file service domain. Valid values are: temporary,
                          appDataContainer, appGroupDataContainer,
                          systemCrashLogs. You must specify a valid domain and
                          identifier pair. Certain domains must be accompanied
                          by an identifier that provides additional context.
                          For example, if the domain is an app data container,
                          the identifier is the bundle ID of the app. For
                          temporary directories, the identifier is a unique
                          client-provided string which is used to get your own
                          space, separate from those of other clients.
  --domain-identifier <domain-identifier>
                          A unique string used to provide additional context to
                          the domain.
  -r, --remove-existing-content <remove-existing-content>
                          Whether to remove files from the destination
                          directory on the device. Only used when transferring
                          directories. (default: false)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info appIcon

```text
OVERVIEW: Request app icon generation from this device.

This command searches for an app installed on this device and requests for its
icon to be generated. You can hint to the device that you want a certain size
and scale using --height, --width, and --scale options, but only supported
sizes will be returned, so you may end up getting a different size or scale
than what you requested. By default, we do not allow placeholder icons to be
returned.

USAGE: devicectl device info appIcon [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --app-bundle-id <app bundle identifier>
                          Look for app icon information with the given
                          application bundle identifier on device.
        Note: If both app-bundle-id and app-path are provided, only app-path
        will be used.
  --app-path <app path>   Look for app icon information at the given
                          application path on device.
        Note: If both app-bundle-id and app-path are provided, only app-path
        will be used.
  --allow-placeholder <allow placeholder>
                          Allow placeholder icons to be generated. (default:
                          false)
        Note: Passing `true` will allow placeholder icons to be returned.
        Allowing placeholder icons will ensure no I/O is done on device. By
        default we do not allow placeholder icons.
  --width <width>         Request app icon generation with the specified width.
                          Since the underlying OS will only return icons in
                          supported sizes, this request may not be honored. By
                          default the icon is returned using the default
                          supported width for the platform (usually 1024).
                          (default: 0.0)
  --height <height>       Request app icon generation with the specified
                          height. Since the underlying OS will only return
                          icons in supported sizes, this request may not be
                          honored. By default the icon is returned using the
                          default supported height for the platform (usually
                          1024). (default: 0.0)
  --scale <scale>         Request app icon generation with the specified scale.
                          Since the underlying OS will only return icons in
                          supported sizes, this request may not be honored.
                          Default: 1.0. (default: 1.0)
  --destination <destination>
                          Write the image (in png format) to the provided file
                          on the host device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info appResize

```text
OVERVIEW: Get the current resizable app session state.

Queries the device for the current state of the resizable app session. The
target display is automatically discovered by finding a display whose name
contains "Resizable".

Note: This command requires an active resizable app session on the device. It
will fail if no session is running.

USAGE: devicectl device info appResize --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info appearance

```text
OVERVIEW: Get Device UI Appearance Information

Get the current user interface style (light/dark) and other appearance settings
for a device (if supported).

USAGE: devicectl device info appearance --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info apps

```text
OVERVIEW: List apps installed on the device.

This command prints the list of apps that are installed on the device.

USAGE: devicectl device info apps [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --include-app-clips/--no-include-app-clips
                          Display App Clip apps. (default:
                          --no-include-app-clips)
        This has no effect on non-iOS platforms.
  --include-removable-apps/--no-include-removable-apps
                          Display apps that can be removed. (default:
                          --include-removable-apps)
        On embedded platforms The value of this property will be `true` for all
        3rd party applications
        and for the subset of system applications that have opted into app
        deletion.

        On macOS, we consider apps that cannot be deleted without disabling SIP
        or without re-blessing the signed system volume to be non-deleteable.

        Such apps exist on the signed system volume and have a URL prefixed
        with `/System`.
  --include-default-apps/--no-include-default-apps
                          Display default apps. (default:
                          --no-include-default-apps)
        An app is considered "default" if it is not a developer app. By
        default, only
        developer apps are included.
  --require-container-access
                          Only display apps with accessible data containers.
        Container access requires the app to be:
        - Third-party (not system app)
        - Installed via Xcode (profile validated)
        - Not enterprise signed

        On internal builds with DDI mounted, more apps are accessible.
  --include-app-group-identifiers
                          Include app group identifiers for
                          container-accessible apps.
        When enabled, each container-accessible app will include
        the list of app groups it belongs to.
  --include-container-paths
                          Include container paths for container-accessible apps.
        When enabled, each container-accessible app will include
        its data container path, bundle container path, and
        group container paths.
  --include-all-apps      Display all apps.
        Same as using:
        --include-app-clips
        --include-default-apps
        --include-removable-apps

        Other filtering options are ignored.
  --bundle-id <bundle identifier>
                          Display apps matching the given bundle identifier
                          exactly.

FILTERING OPTIONS:
  -s, --search <search>   A plain-text search string used to filter results.
        Performs a case-insensitive substring match across all columns. Rows
        where any column contains the search string are included in the output.
         This searches all possible columns, not just visible ones.

        E.g. `--search iPhone` or `-s mac`

        For advanced filtering with specific fields and operators, use
        `--filter` instead.
  --filter <filter>       An NSPredicate expression used to filter the list of
                          items shown.
        The attribute name can be the column's name from either the table-based
        output or a fully qualified JSON field identifier from the JSON output.

        Common operators: = (equals), CONTAINS, BEGINSWITH, ENDSWITH, AND, OR,
        NOT.

        Examples:
          --filter "Name CONTAINS 'iPhone'"
          --filter "Identifier = '00008101-000A0C123456001E'"
          --filter "hardwareProperties.platform BEGINSWITH 'mac'"
          --filter "Name CONTAINS 'iPad' AND State = 'available'"

        For simple text matching across all columns, use `--search` instead.
  --sort-by <sort-by>     If specified, a key path by which to sort results.
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info audio

```text
OVERVIEW: Get device audio settings

Get the current audio output device, audio input device, and volume level for a
device (if supported).

USAGE: devicectl device info audio --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info authListing

```text
OVERVIEW: Get the device's AuthListing identifiers.

This command shows the identifiers required for AuthListing this device with
TATSU.

USAGE: devicectl device info authListing --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info ddiServices

```text
OVERVIEW: Get information on the developer disk image services on the device.

This command gets information about the developer disk image services on the
device (if they are currently enabled).

USAGE: devicectl device info ddiServices --device <uuid|ecid|serial_number|udid|name|dns_name> [--auto-mount-ddis] [--no-auto-mount-ddis] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --auto-mount-ddis/--no-auto-mount-ddis
                          Checks if the device’s mounted DDI is current and
                          updates it before retrieving the DDI metadata.
                          (default: --auto-mount-ddis)
        By default, the metadata will be retrieved. If this option is disabled,
        the metadata will be whatever the current state of the Core Device
        built-in services are, without updating or mounting the developer disk
        image on the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info details

```text
OVERVIEW: Get information about the current device.

This command gets device information for the requested device. This may involve
connecting to the device and accessing Core Device built-in services. If we
cannot connect to the device (or otherwise fail to get information) the best
information available is returned.

USAGE: devicectl device info details --device <uuid|ecid|serial_number|udid|name|dns_name> [--show <show>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --show <show>           Controls which fields are displayed. 'summary' shows
                          the default set. 'detailed' includes all stable
                          fields and capabilities. 'diagnostics' includes
                          everything, but its JSON output is NOT safe to depend
                          on since it includes device properties that are not
                          ABI stable. (values: summary, detailed, diagnostics;
                          default: summary)
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info displays

```text
OVERVIEW: Get the device's current display information.

This command shows the current display/screen information for this device.

USAGE: devicectl device info displays --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info files

```text
OVERVIEW: List files on the device.

This command prints a list of the files at a specified path on the device.

USAGE: devicectl device info files [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name> --domain-type <domain-type>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

FILE OPTIONS:
  --username <username>   The username of the user we should target. Only
                          relevant for certain domains.
  --domain-type <domain-type>
                          The file service domain. Valid values are: temporary,
                          appDataContainer, appGroupDataContainer,
                          systemCrashLogs. You must specify a valid domain and
                          identifier pair. Certain domains must be accompanied
                          by an identifier that provides additional context.
                          For example, if the domain is an app data container,
                          the identifier is the bundle ID of the app. For
                          temporary directories, the identifier is a unique
                          client-provided string which is used to get your own
                          space, separate from those of other clients.
  --domain-identifier <domain-identifier>
                          A unique string used to provide additional context to
                          the domain.

COMMAND OPTIONS:
  --subdirectory <subdirectory>
                          A subdirectory within the domain. If not specified,
                          defaults to the root.
  -r, --recurse/--no-recurse
                          Recurse into subdirectories.  (default: --recurse)

FILTERING OPTIONS:
  -s, --search <search>   A plain-text search string used to filter results.
        Performs a case-insensitive substring match across all columns. Rows
        where any column contains the search string are included in the output.
         This searches all possible columns, not just visible ones.

        E.g. `--search iPhone` or `-s mac`

        For advanced filtering with specific fields and operators, use
        `--filter` instead.
  --filter <filter>       An NSPredicate expression used to filter the list of
                          items shown.
        The attribute name can be the column's name from either the table-based
        output or a fully qualified JSON field identifier from the JSON output.

        Common operators: = (equals), CONTAINS, BEGINSWITH, ENDSWITH, AND, OR,
        NOT.

        Examples:
          --filter "Name CONTAINS 'iPhone'"
          --filter "Identifier = '00008101-000A0C123456001E'"
          --filter "hardwareProperties.platform BEGINSWITH 'mac'"
          --filter "Name CONTAINS 'iPad' AND State = 'available'"

        For simple text matching across all columns, use `--search` instead.
  --sort-by <sort-by>     If specified, a key path by which to sort results.
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info lockState

```text
OVERVIEW: Get the current locked state of the device.

This command gets the current locked state of a device. This command does
nothing for macOS devices.

USAGE: devicectl device info lockState --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info mountpoint

```text
OVERVIEW: Get the mount point for the device-specific data folder on the host.

Mounts the device file system if needed and returns the path to the
device-specific folder.

USAGE: devicectl device info mountpoint --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device info processes

```text
OVERVIEW: List currently running processes on the device.

This command prints the list of processes running on the device.

USAGE: devicectl device info processes --device <uuid|ecid|serial_number|udid|name|dns_name> [--search <search>] [--filter <filter>] [--sort-by <sort-by>] [--columns <columns> ...] [--hide-default-columns] [--hide-headers] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

FILTERING OPTIONS:
  -s, --search <search>   A plain-text search string used to filter results.
        Performs a case-insensitive substring match across all columns. Rows
        where any column contains the search string are included in the output.
         This searches all possible columns, not just visible ones.

        E.g. `--search iPhone` or `-s mac`

        For advanced filtering with specific fields and operators, use
        `--filter` instead.
  --filter <filter>       An NSPredicate expression used to filter the list of
                          items shown.
        The attribute name can be the column's name from either the table-based
        output or a fully qualified JSON field identifier from the JSON output.

        Common operators: = (equals), CONTAINS, BEGINSWITH, ENDSWITH, AND, OR,
        NOT.

        Examples:
          --filter "Name CONTAINS 'iPhone'"
          --filter "Identifier = '00008101-000A0C123456001E'"
          --filter "hardwareProperties.platform BEGINSWITH 'mac'"
          --filter "Name CONTAINS 'iPad' AND State = 'available'"

        For simple text matching across all columns, use `--search` instead.
  --sort-by <sort-by>     If specified, a key path by which to sort results.
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device install app

```text
OVERVIEW: Installs an app.

This command installs an app bundle (with a .app extension) on the device.

USAGE: devicectl device install app [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name> <path>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <path>                  The path to the application to be installed on the
                          device

FILTERING OPTIONS:
  -s, --search <search>   A plain-text search string used to filter results.
        Performs a case-insensitive substring match across all columns. Rows
        where any column contains the search string are included in the output.
         This searches all possible columns, not just visible ones.

        E.g. `--search iPhone` or `-s mac`

        For advanced filtering with specific fields and operators, use
        `--filter` instead.
  --filter <filter>       An NSPredicate expression used to filter the list of
                          items shown.
        The attribute name can be the column's name from either the table-based
        output or a fully qualified JSON field identifier from the JSON output.

        Common operators: = (equals), CONTAINS, BEGINSWITH, ENDSWITH, AND, OR,
        NOT.

        Examples:
          --filter "Name CONTAINS 'iPhone'"
          --filter "Identifier = '00008101-000A0C123456001E'"
          --filter "hardwareProperties.platform BEGINSWITH 'mac'"
          --filter "Name CONTAINS 'iPad' AND State = 'available'"

        For simple text matching across all columns, use `--search` instead.
  --sort-by <sort-by>     If specified, a key path by which to sort results.
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device notification post

```text
OVERVIEW: Post a Darwin notification to a device.

Posts a darwin notification with the given name to a device.

USAGE: devicectl device notification post --device <uuid|ecid|serial_number|udid|name|dns_name> --name <name> ... [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --name <name>           The name of the Darwin notification.
        This can be passed multiple times to post multiple Darwin notifications.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device notification observe

```text
OVERVIEW: Observe a Darwin notification on a device.

Note that this command will wait for 300 seconds by default before exiting. You
can override this by providing a different --timeout value.

USAGE: devicectl device notification observe --device <uuid|ecid|serial_number|udid|name|dns_name> --name <name> ... [--session-timeout <session-timeout>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --name <name>           The name of the Darwin notification.
        This can be passed multiple times to observe multiple Darwin
        notifications.
  --session-timeout <session-timeout>
                          Optional parameter for the amount of time (in
                          seconds) to wait before exiting. Default: 300
                          (default: 300)
        Note that this is a separate parameter from, and must be less than, the
        global --timeout.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device orientation get

```text
OVERVIEW: Get Device Orientation

Get the current orientation for a device (if supported)

USAGE: devicectl device orientation get --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device orientation rotate

```text
OVERVIEW: Rotate Device Orientation

Set the current orientation for a device by rotating relative to the current
orientation

USAGE: devicectl device orientation rotate --device <uuid|ecid|serial_number|udid|name|dns_name> <direction> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <direction>             The rotation direction (values: left, right, l, r)
        Valid values: right (r) or left (l)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device orientation set

```text
OVERVIEW: Set Device Orientation

Set the current orientation for a device (if supported)

USAGE: devicectl device orientation set --device <uuid|ecid|serial_number|udid|name|dns_name> <orientation> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <orientation>           The new orientation (values: portrait,
                          portraitUpsideDown, landscapeLeft, landscapeRight,
                          faceUp, faceDown, p, pu, ll, lr, fd, fu)
        Valid values: portrait (p), portraitUpsideDown (pu), landscapeLeft
        (ll), landscapeRight (lr), faceDown (fd), or faceUp fu)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pairings list

```text
OVERVIEW: List paired devices.

This command allows you to list devices that have been paired with this device.

USAGE: devicectl device pairings list --device <uuid|ecid|serial_number|udid|name|dns_name> [--search <search>] [--filter <filter>] [--sort-by <sort-by>] [--columns <columns> ...] [--hide-default-columns] [--hide-headers] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

FILTERING OPTIONS:
  -s, --search <search>   A plain-text search string used to filter results.
        Performs a case-insensitive substring match across all columns. Rows
        where any column contains the search string are included in the output.
         This searches all possible columns, not just visible ones.

        E.g. `--search iPhone` or `-s mac`

        For advanced filtering with specific fields and operators, use
        `--filter` instead.
  --filter <filter>       An NSPredicate expression used to filter the list of
                          items shown.
        The attribute name can be the column's name from either the table-based
        output or a fully qualified JSON field identifier from the JSON output.

        Common operators: = (equals), CONTAINS, BEGINSWITH, ENDSWITH, AND, OR,
        NOT.

        Examples:
          --filter "Name CONTAINS 'iPhone'"
          --filter "Identifier = '00008101-000A0C123456001E'"
          --filter "hardwareProperties.platform BEGINSWITH 'mac'"
          --filter "Name CONTAINS 'iPad' AND State = 'available'"

        For simple text matching across all columns, use `--search` instead.
  --sort-by <sort-by>     If specified, a key path by which to sort results.
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pairings pair

```text
OVERVIEW: Create a new watch and phone pair.

This command creates a new watch and phone pairing.

USAGE: devicectl device pairings pair --phone <uuid|ecid|serial_number|udid|name|dns_name> --watch <uuid|ecid|serial_number|udid|name|dns_name> ... [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

COMMAND OPTIONS:
  -p, --phone <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.
  -w, --watch <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pairings set-active

```text
OVERVIEW: Make the watch and phone pairing active.

This command allows you to make an existing phone and watch pairing active.

USAGE: devicectl device pairings set-active --phone <uuid|ecid|serial_number|udid|name|dns_name> --watch <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

COMMAND OPTIONS:
  -p, --phone <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.
  -w, --watch <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pairings unpair

```text
OVERVIEW: Unpair a paired watch and phone.

This command allows you to unpair a paired watch and phone.

USAGE: devicectl device pairings unpair --phone <uuid|ecid|serial_number|udid|name|dns_name> --watch <uuid|ecid|serial_number|udid|name|dns_name> ... [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

COMMAND OPTIONS:
  -p, --phone <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.
  -w, --watch <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pasteboard copy

```text
OVERVIEW: Copy data to the device pasteboard.

Reads data from stdin (or files specified by --file) and places it on the
device pasteboard.

By default, the data is treated as UTF-8 text and written using multiple text
UTI types (public.utf8-plain-text, public.plain-text, public.text) to maximize
compatibility. Use --type to specify a single UTI type for non-text data.

When multiple --file options are provided, each file becomes a separate
pasteboard item.

Examples:
  echo "hello" | devicectl device pasteboard copy -d <device>
  devicectl device pasteboard copy --file image.png --type public.png -d
<device>
  devicectl device pasteboard copy --file a.txt --file b.txt -d <device>

USAGE: devicectl device pasteboard copy --device <uuid|ecid|serial_number|udid|name|dns_name> [--type <uti>] [--file <path> ...] [--device-pasteboard <device-pasteboard>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --type <uti>            The UTI type to use for the pasteboard data.
        When not specified, the data is written as plain text using multiple
        text UTI types.
  --file <path>           Read data from file(s) instead of stdin.
        Multiple --file options can be provided. Each file becomes a separate
        item on the pasteboard, added in order.
  --device-pasteboard <device-pasteboard>
                          Name of the device pasteboard. (default: general)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pasteboard paste

```text
OVERVIEW: Paste device pasteboard contents to stdout.

Reads the device pasteboard and writes the contents to stdout.

Without --type, searches for text content in priority order:
public.utf8-plain-text, public.plain-text, public.text, public.url. With
--type, extracts that specific UTI's raw data.

Only the requested type's data is transferred from the device.

Because the pasteboard payload is the command's stdout output, '--json-output
-' is not supported; pass '--json-output <path>' instead.

Examples:
  devicectl device pasteboard paste -d <device>
  devicectl device pasteboard paste --type public.png -d <device> > image.png

USAGE: devicectl device pasteboard paste --device <uuid|ecid|serial_number|udid|name|dns_name> [--type <uti>] [--item <index>] [--device-pasteboard <device-pasteboard>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --type <uti>            The UTI type to extract from the pasteboard.
        When not specified, searches for text types in priority order.
  --item <index>          The pasteboard item index to paste (0-based).
                          (default: 0)
        When the pasteboard contains multiple items, this selects which one to
        output. Defaults to the first item.
  --device-pasteboard <device-pasteboard>
                          Name of the device pasteboard. (default: general)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pasteboard info

```text
OVERVIEW: Show information about the device pasteboard.

Displays all items and their flavors with type names and data sizes. No actual
data is transferred from the device.

USAGE: devicectl device pasteboard info --device <uuid|ecid|serial_number|udid|name|dns_name> [--device-pasteboard <device-pasteboard>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --device-pasteboard <device-pasteboard>
                          Name of the device pasteboard. (default: general)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pasteboard monitor

```text
OVERVIEW: Monitor device pasteboard for changes.

Watches the device pasteboard for changes and reports each change event. This
command will wait for 300 seconds by default before exiting.

USAGE: devicectl device pasteboard monitor --device <uuid|ecid|serial_number|udid|name|dns_name> [--session-timeout <session-timeout>] [--device-pasteboard <device-pasteboard>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --session-timeout <session-timeout>
                          Optional parameter for the amount of time (in
                          seconds) to wait before exiting. Default: 300
                          (default: 300)
        Note that this is a separate parameter from, and must be less than, the
        global --timeout.
  --device-pasteboard <device-pasteboard>
                          Name of the device pasteboard. (default: general)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device pasteboard transfer

```text
OVERVIEW: Transfer pasteboard contents between host and device.

USAGE: devicectl device pasteboard transfer [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  to                      Transfer the host pasteboard to the device.
  from                    Transfer the device pasteboard to the host.

  See 'devicectl help device pasteboard transfer <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


##### devicectl device pasteboard sync-with-host

```text
OVERVIEW: Bidirectional pasteboard sync between host and device.

Continuously synchronizes the pasteboard between the host and device. When the
device pasteboard changes, the host pasteboard is updated, and vice versa. This
command will run for 300 seconds by default before exiting.

USAGE: devicectl device pasteboard sync-with-host [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --session-timeout <session-timeout>
                          Optional parameter for the amount of time (in
                          seconds) to wait before exiting. Default: 300
                          (default: 300)
        Note that this is a separate parameter from, and must be less than, the
        global --timeout.
  --device-pasteboard <device-pasteboard>
                          Name of the device pasteboard. (default: general)
  --host-pasteboard <host-pasteboard>
                          Name of the host pasteboard. (default: general)
  --data-policy-from-device <policy>
                          Data policy for device-to-host transfers. (values:
                          match-source, all-resolved, all-promised,
                          promise-secondary, threshold-data)
        Controls which types include inline data vs. promises when reading from
        the device pasteboard. Defaults to threshold-data.
  --data-policy-to-device <policy>
                          Data policy for host-to-device transfers. (values:
                          match-source, all-resolved, all-promised,
                          promise-secondary, threshold-data)
        Controls which types include inline data vs. promises when writing to
        the device pasteboard. Defaults to threshold-data.
  --data-policy <policy>  Data policy for both directions. (values:
                          match-source, all-resolved, all-promised,
                          promise-secondary, threshold-data)
        Sets the data policy for both device-to-host and host-to-device
        transfers. Overridden by --data-policy-from-device or
        --data-policy-to-device if specified.
  --data-threshold-bytes <bytes>
                          Size threshold in bytes for threshold-data mode.
                          (default: 16384)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process awaitTermination

```text
OVERVIEW: Waits for the termination of a remote process.

This command waits for the termination of a process on the device and returns
the exit status.

USAGE: devicectl device process awaitTermination --device <uuid|ecid|serial_number|udid|name|dns_name> --pid <pid> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  -p, --pid <pid>         The process ID to monitor.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process launch

```text
OVERVIEW: Launch a remote application.

This command launches an application on a device and passes it specific
arguments.

If you want to set environment variables in the resulting environment, set them
in the calling environment with a DEVICECTL_CHILD_ prefix.

Once the application has launched, you can attach to it using LLDB. For
example, if you have an iPhone named 'iPhone' connected to your Mac, and your
application running on the iPhone has the process identifier of 10684, you can
debug your application using the following steps:

$ xcrun lldb
(lldb) device select iPhone
(lldb) device process attach -p 10684

See LLDB's help for information about all supported commands.

--console bridges the app's stdout to devicectl's stdout, so '--json-output -'
is not supported with --console; pass '--json-output <path>' instead.

USAGE: devicectl device process launch [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name> <bundle-identifier-or-path> [<command-line-arguments> ...]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  -u, --user <user>       The user ID or name to run as.
  -e, --environment-variables <environment-variables>
                          A JSON-encoded dictionary of environment variables
                          and their values to provide to the process.
        Keys and values must be strings.
        Example: '{"PATH": "/usr/local/bin", "REPORTTIME": "2", "LANG":
        "en_US.UTF-8"}'

        Note: Using the environment-variables flag will override the caller
        environment variables prefixed with DEVICECTL_CHILD_.
  <bundle-identifier-or-path>
                          The bundle identifier of or path to the remote
                          application.
  <command-line-arguments>
                          Arguments to pass to the remote application.
  --start-stopped         Launches the app in a suspended state, waiting for a
                          debugger.
  --working-directory <working-directory>
                          The initial working directory for the spawned process.
  --arch <arch>           The architecture slice to prefer when launching the
                          application.
  --payload-url <payload-url>
                          A URL to pass to the application for it to open
                          during launch.
  --activate/--no-activate
                          Launches the application in the foreground. (default:
                          --activate)
        Whether or not to activate the application when starting it. Not
        supported on all platforms.
  --terminate-existing    Terminates any already-running instances of the app
                          prior to launch. Not supported on all platforms.
  --display <display>     The unique identifier of the display to launch the
                          app on.
        Use 'devicectl device info displays' to list available displays and
        their unique identifiers. Not supported on all platforms.
  --launch-persistent-identifier <launch-persistent-identifier>
                          The base64-encoded Launch Services persistent
                          identifier of a recently installed app.
        This is the 'launchServicesIdentifier' value returned by 'devicectl
        device install app'. It allows the system to synchronize the
        distributed knowledge of an app installation.
  --console               Attaches the application to the console and waits for
                          it to exit.
        devicectl will wait for the app to terminate. Catchable signals sent to
        devicectl are forwarded to the app. If the app is not already running,
        its standard streams will be connected to devicectl's standard streams.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process openURL

```text
OVERVIEW: Open a URL on the device.

This command opens a URL on the device using the default application
registered to handle that URL type.

For example, to open a web page:
    devicectl device process openURL https://apple.com --device <device>

To open a custom URL scheme:
    devicectl device process openURL myapp://action --device <device>

USAGE: devicectl device process openURL --device <uuid|ecid|serial_number|udid|name|dns_name> <url> [--activate] [--no-activate] [--terminate-existing] [--display <display>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <url>                   The URL to open on the device.
  --activate/--no-activate
                          Launches the application in the foreground. (default:
                          --activate)
        Whether or not to activate the application when starting it. Not
        supported on all platforms.
  --terminate-existing    Terminates any already-running instances of the app
                          prior to launch. Not supported on all platforms.
  --display <display>     The unique identifier of the display to open the URL
                          on.
        Use 'devicectl device info displays' to list available displays and
        their unique identifiers. Not supported on all platforms.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process resume

```text
OVERVIEW: Resume a process on a device.

This command attempts to resume a process on a device.

USAGE: devicectl device process resume --device <uuid|ecid|serial_number|udid|name|dns_name> --pid <pid> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  -p, --pid <pid>         The process identifier to resume.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process sendMemoryWarning

```text
OVERVIEW: Sends a memory pressure warning to a process on a device.

This command attempts to send a memory pressure warning to a process on a
device.

USAGE: devicectl device process sendMemoryWarning --device <uuid|ecid|serial_number|udid|name|dns_name> --pid <pid> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  -p, --pid <pid>         The process identifier to target.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process signal

```text
OVERVIEW: Send a signal to a process on a device.

This command attempts to send a signal to a process on a device.

USAGE: devicectl device process signal --device <uuid|ecid|serial_number|udid|name|dns_name> --pid <pid> --signal <signal> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  -p, --pid <pid>         The process identifier to send a signal to.
  -s, --signal <signal>   The signal to send to a process. See 'man signal' for
                          a list of signals.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process suspend

```text
OVERVIEW: Suspend a process on a device.

This command attempts to suspend a process on a device.

USAGE: devicectl device process suspend --device <uuid|ecid|serial_number|udid|name|dns_name> --pid <pid> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  -p, --pid <pid>         The process identifier to suspend.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device process terminate

```text
OVERVIEW: Terminate a process on a device.

  "This command attempts to terminate a process on a device.

USAGE: devicectl device process terminate --device <uuid|ecid|serial_number|udid|name|dns_name> --pid <pid> [--kill] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  -p, --pid <pid>         The process identifier to terminate.
  --kill                  Do not allow the target process to catch the
                          termination signal (i.e. use SIGKILL instead of
                          SIGTERM).

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device profile install

```text
OVERVIEW: Install one or more profiles on a device.

This command installs profile(s) on the device. Both provisioning profiles
(.mobileprovision) and configuration profiles (.mobileconfig) are supported.

The profile type is auto-detected from the file extension, or can be specified
explicitly using --type.

Multiple profiles can be specified and will be installed in a batch operation.
Each profile will be validated before installation.
Use 'devicectl device profile validate' to check a profile without installing
it.

USAGE: devicectl device profile install --device <uuid|ecid|serial_number|udid|name|dns_name> <paths> ... [--type <type>] [--replace-existing] [--no-replace-existing] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <paths>                 The path(s) to the profile(s) to install
                          (.mobileprovision or .mobileconfig)
  --type <type>           Force profile type (provisioning or configuration).
                          Auto-detected from file extension if not specified.
                          (values: provisioning, configuration)
  --replace-existing/--no-replace-existing
                          Allow replacing existing profiles with the same
                          identifier (default: --replace-existing)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device profile list

```text
OVERVIEW: List profiles installed on a device.

This command lists all profiles installed on the device, including both
provisioning profiles (.mobileprovision) and configuration profiles
(.mobileconfig).

Use --type to filter by profile type.

USAGE: devicectl device profile list [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --type <type>           Filter by profile type (provisioning or
                          configuration) (values: provisioning, configuration)

FILTERING OPTIONS:
  -s, --search <search>   A plain-text search string used to filter results.
        Performs a case-insensitive substring match across all columns. Rows
        where any column contains the search string are included in the output.
         This searches all possible columns, not just visible ones.

        E.g. `--search iPhone` or `-s mac`

        For advanced filtering with specific fields and operators, use
        `--filter` instead.
  --filter <filter>       An NSPredicate expression used to filter the list of
                          items shown.
        The attribute name can be the column's name from either the table-based
        output or a fully qualified JSON field identifier from the JSON output.

        Common operators: = (equals), CONTAINS, BEGINSWITH, ENDSWITH, AND, OR,
        NOT.

        Examples:
          --filter "Name CONTAINS 'iPhone'"
          --filter "Identifier = '00008101-000A0C123456001E'"
          --filter "hardwareProperties.platform BEGINSWITH 'mac'"
          --filter "Name CONTAINS 'iPad' AND State = 'available'"

        For simple text matching across all columns, use `--search` instead.
  --sort-by <sort-by>     If specified, a key path by which to sort results.
  --columns <columns>     If specified, additional data columns to print.
                          Specify '*' (in quotes) for all data columns.
  --hide-default-columns  Hide default data columns and only print those
                          specified with --columns.
  --hide-headers          Hide data column headers.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device profile remove

```text
OVERVIEW: Remove one or more profiles from a device.

This command removes profile(s) from the device.

For provisioning profiles, specify the UUID (e.g.,
"12345678-1234-1234-1234-123456789ABC").
For configuration profiles, specify the payload identifier (e.g.,
"com.example.myprofile").

The profile type is auto-detected based on the identifier format, or can be
specified
explicitly using --type.

Use 'devicectl device profile list' to see available profiles and their
identifiers.

USAGE: devicectl device profile remove --device <uuid|ecid|serial_number|udid|name|dns_name> <identifiers> ... [--type <type>] [--force-removal] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <identifiers>           The identifier(s) of the profile(s) to remove. UUIDs
                          for provisioning profiles, payload identifiers for
                          configuration profiles.
  --type <type>           Profile type (provisioning or configuration). If not
                          specified, auto-detects based on identifier format.
                          (values: provisioning, configuration)
  --force-removal         Force removal even if profile is not found on device

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device profile validate

```text
OVERVIEW: Validate one or more profiles without installing them.

This command validates profile(s) without installing them.
Multiple profiles can be specified and will be validated in a batch operation.

Supported profile types:
  - Provisioning profiles (.mobileprovision): Validation includes signature
verification,
    expiration checking, and format validation.
  - Configuration profiles (.mobileconfig): Validation includes format
checking,
    expiration checking, and payload validation.

The profile type is auto-detected from the file extension, or can be specified
explicitly using the --type flag.

This is a local operation and does not require a device connection.

USAGE: devicectl device profile validate <paths> ... [--type <type>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

COMMAND OPTIONS:
  <paths>                 The path(s) to the profile(s) to validate
                          (.mobileprovision or .mobileconfig)
  --type <type>           The type of profile to validate (provisioning or
                          configuration). Auto-detected from file extension if
                          not specified. (values: provisioning, configuration)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device settings appearance

```text
OVERVIEW: Set device user interface appearance

Set the user interface style (light/dark), look and feel, text size, increase
contrast, reduce motion, reduce transparency, show borders, Liquid Glass
opacity, and/or color filter for a device (if supported).
Use 'devicectl device info appearance' to get the current appearance settings.

USAGE: devicectl device settings appearance [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --mode <mode>           The user interface style to set (values: light, dark,
                          l, d)
        Valid values: light or dark
  --look-and-feel <look-and-feel>
                          The look and feel to set (values: clear, tinted, c, t)
        Valid values: clear, tinted
  --text-size <text-size> The text size to set (values: extra-small, small,
                          medium, large, extra-large, extra-extra-large,
                          extra-extra-extra-large, xs, s, m, l, xl, xxl, xxxl)
        Valid values: extra-small, small, medium, large, extra-large,
        extra-extra-large, extra-extra-extra-large
  --increase-contrast <increase-contrast>
                          Enable or disable increased contrast (values: on, off)
        Valid values: on, off
  --reduce-motion <reduce-motion>
                          The reduce motion setting (values: on, off)
        Valid values: on, off
  --reduce-transparency <reduce-transparency>
                          The reduce transparency setting (values: on, off)
        Valid values: on, off
  --show-borders <show-borders>
                          The show borders setting (values: on, off)
        Valid values: on, off
  --liquid-glass-opacity <liquid-glass-opacity>
                          The Liquid Glass opacity level
        A value from 0.0 (fully translucent) to 1.0 (fully opaque)
  --color-filter <color-filter>
                          Enable or disable the color filter (values: on, off)
        Valid values: on, off
  --color-filter-type <color-filter-type>
                          The color filter type (values: grayscale, protanopia,
                          deuteranopia, tritanopia, gray, red-green, green-red,
                          blue-yellow)
        Valid values: grayscale, protanopia (red-green), deuteranopia
        (green-red), tritanopia (blue-yellow)
  --color-filter-intensity <color-filter-intensity>
                          The color filter intensity (does not apply to
                          grayscale)
        A value from 0.25 to 1.0

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device settings audio

```text
OVERVIEW: Set device audio settings

Set the audio output device, audio input device, and/or volume level for a
device (if supported).
Use 'devicectl device info audio' to get the current audio settings.

USAGE: devicectl device settings audio --device <uuid|ecid|serial_number|udid|name|dns_name> [--output-device <output-device>] [--input-device <input-device>] [--volume <volume>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --output-device <output-device>
                          The audio output device to use
        Use 'systemDefault' for the host system's default audio device, or a
        device identifier string to pin to a specific device.
  --input-device <input-device>
                          The audio input device to use
        Use 'systemDefault' for the host system's default audio device, or a
        device identifier string to pin to a specific device.
  --volume <volume>       The volume level to set (0–100)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device settings biometrics

```text
OVERVIEW: Query or control biometric settings.

Query, enable, or disable biometrics on a device. Pass `--enable` or
`--disable` to change the enrollment state of all supported biometric types
(Touch ID, Face ID, Optic ID). With no flag, the command reports the current
enrollment state for each supported biometric type without making any changes.

USAGE: devicectl device settings biometrics --device <uuid|ecid|serial_number|udid|name|dns_name> [--enable] [--disable] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --enable                Enable biometrics on the device.
  --disable               Disable biometrics on the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device settings reset

```text
OVERVIEW: Reset a device’s content and settings.

This will restore the device to factory settings and erase all user content
and files.

USAGE: devicectl device settings reset --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device simulate biometrics

```text
OVERVIEW: Simulate biometric authentication events.

Simulate biometric authentication events on a device. The device must have
biometrics enabled for this to take effect. This command acts on all supported
biometric types.

USAGE: devicectl device simulate biometrics --device <uuid|ecid|serial_number|udid|name|dns_name> --success --failure [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --success               Simulate a successful biometric match.
  --failure               Simulate a failed biometric match.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl device simulate location

```text
OVERVIEW: Simulate device location.

Simulate a device being at a specific location or moving along a route.

USAGE: devicectl device simulate location [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  clear                   Clear any active location simulation
  coordinate              Set location to specific coordinates
  list                    List available location scenarios
  route                   Simulate movement along waypoints
  scenario                Set location using a pre-defined scenario or from a
                          file

  See 'devicectl help device simulate location <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


##### devicectl device simulate statusBar

```text
OVERVIEW: Simulate device status bar appearance.

Customize the appearance of the device's status bar for screenshots and UI
testing. Override indicators like time, network type, signal strength, and
battery level.

USAGE: devicectl device simulate statusBar [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>] <subcommand>

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.

SUBCOMMANDS:
  clear                   Clear any active status bar overrides
  override                Override status bar indicators with custom values
  preset                  Apply a preset status bar configuration
  show                    Show currently active status bar overrides

  See 'devicectl help device simulate statusBar <subcommand>' for detailed help.
```

[↑ Back to Command Index](#index)


##### devicectl device uninstall app

```text
OVERVIEW: Uninstalls an app.

This command removes an app from the device.

USAGE: devicectl device uninstall app --device <uuid|ecid|serial_number|udid|name|dns_name> <bundle-identifier> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <bundle-identifier>     The bundle identifier of the application to uninstall.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl manage ddis clean

```text
OVERVIEW: Removes any developer disk images installed on the host.

This command removes any developer disk images installed on the host (in
/Library/Developer/DeveloperDiskImages).

USAGE: devicectl manage ddis clean [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl manage ddis update

```text
OVERVIEW: Update the DDIs installed on the host.

This command updates the set of DDIs installed on the host (in
/Library/Developer/DeveloperDiskImages). By default the DDIs from the selected
Xcode are used to update the host. The user can provide a directory of DDIs to
use instead via the --source-dir flag.

USAGE: devicectl manage ddis update [--source-dir <source-dir> ...] [--clean] [--no-clean] [--include-coredevice] [--no-include-coredevice] [--include-xcode] [--no-include-xcode] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

COMMAND OPTIONS:
  --source-dir <source-dir>
                          Additional absolute path to the directory containing
                          DDIs to install.
        Multiple source directories can be provided by passing in the option
        multiple times.
  --clean/--no-clean      Clean out /Library/Developer/DeveloperDiskImages
                          before updating DDIs (default: --no-clean)
        If set, devicectl will remove /Library/Developer/DeveloperDiskImages
        and replace it with an empty directory before updating the DDIs on the
        host.
  --include-coredevice/--no-include-coredevice
                          Include DDIs from
                          /Library/Developer/CoreDevice/CandidateDDIs as
                          candidate DDIs to consider when updating. (default:
                          --include-coredevice)
        If set, devicectl will include
        /Library/Developer/CoreDevice/CandidateDDIs in the set of DDIs to
        consider when updating. By default, this directory is included.
  --include-xcode/--no-include-xcode
                          Include DDIs from the selected Xcode.app (if present)
                          as candidate DDIs to consider when updating.
                          (default: --include-xcode)
        If set, devicectl will include DDIs present in the selected Xcode.app
        (if present) in the set of DDIs to consider when updating. By default,
        DDIs are included from the selected Xcode.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


##### devicectl manage loggingProfile register

```text
OVERVIEW: Registers the Core Device logging profile on your Mac and optionally
opens System Settings.

Registers a special logging profile on your Mac which allows Core Device to log
all of the data it collects. This profile is useful if you want to collect data
for debugging purposes or for filing feedback reports, and the profile can be
uninstalled at any time. After the logging profile is registered, you must
activate it in System Settings.

USAGE: devicectl manage loggingProfile register [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

[↑ Back to Command Index](#index)


###### devicectl device pasteboard transfer to

```text
OVERVIEW: Transfer the host pasteboard to the device.

Reads the host system pasteboard and writes its contents to the device
pasteboard. All items and their associated types are transferred.

USAGE: devicectl device pasteboard transfer to --device <uuid|ecid|serial_number|udid|name|dns_name> [--data-policy <mode>] [--data-threshold-bytes <bytes>] [--device-pasteboard <device-pasteboard>] [--host-pasteboard <host-pasteboard>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --data-policy <mode>    How to handle pasteboard data transfer. (values:
                          match-source, all-resolved, all-promised,
                          promise-secondary, threshold-data; default:
                          threshold-data)
        match-source: Preserve promise/data state from source.
        all-resolved: Fetch all data eagerly.
        all-promised: Set up all types as promises, fulfilled on demand.
        promise-secondary: Resolve the primary type eagerly, promise the rest.
        threshold-data: Resolve types under --data-threshold-bytes eagerly,
        promise the rest (default).
  --data-threshold-bytes <bytes>
                          Size threshold in bytes for threshold-data mode.
                          (default: 16384)
        Types with data below this size are transferred eagerly; types at or
        above this size are transferred as promises. Only used with
        --data-policy threshold-data.
  --device-pasteboard <device-pasteboard>
                          Name of the device pasteboard. (default: general)
  --host-pasteboard <host-pasteboard>
                          Name of the host pasteboard. (default: general)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device pasteboard transfer from

```text
OVERVIEW: Transfer the device pasteboard to the host.

Reads the device pasteboard and writes its contents to the host system
pasteboard. With data policy modes that produce promises (all-promised,
promise-secondary, threshold-data), the command stays alive to fulfill data
requests until the host pasteboard is overwritten or cancelled.

USAGE: devicectl device pasteboard transfer from --device <uuid|ecid|serial_number|udid|name|dns_name> [--data-policy <mode>] [--data-threshold-bytes <bytes>] [--device-pasteboard <device-pasteboard>] [--host-pasteboard <host-pasteboard>] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --data-policy <mode>    How to handle pasteboard data transfer. (values:
                          match-source, all-resolved, all-promised,
                          promise-secondary, threshold-data; default:
                          threshold-data)
        match-source: Preserve promise/data state from source.
        all-resolved: Fetch all data eagerly.
        all-promised: Set up all types as promises, fulfilled on demand.
        promise-secondary: Resolve the primary type eagerly, promise the rest.
        threshold-data: Resolve types under --data-threshold-bytes eagerly,
        promise the rest (default).
  --data-threshold-bytes <bytes>
                          Size threshold in bytes for threshold-data mode.
                          (default: 16384)
        Types with data below this size are transferred eagerly; types at or
        above this size are transferred as promises. Only used with
        --data-policy threshold-data.
  --device-pasteboard <device-pasteboard>
                          Name of the device pasteboard. (default: general)
  --host-pasteboard <host-pasteboard>
                          Name of the host pasteboard. (default: general)

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate location clear

```text
OVERVIEW: Clear any active location simulation

Stop any ongoing location simulation and return the device to using its actual
location.

USAGE: devicectl device simulate location clear --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate location coordinate

```text
OVERVIEW: Set location to specific coordinates

Set the device to a specific latitude and longitude. The simulation will
continue until cleared.

USAGE: devicectl device simulate location coordinate --device <uuid|ecid|serial_number|udid|name|dns_name> --latitude <latitude> --longitude <longitude> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --latitude <latitude>   The latitude of the location
        Latitude in decimal degrees (e.g., 37.7749 for San Francisco).
  --longitude <longitude> The longitude of the location
        Longitude in decimal degrees (e.g., -122.4194 for San Francisco).

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate location list

```text
OVERVIEW: List available location scenarios

List all pre-defined location scenarios available for the device.

USAGE: devicectl device simulate location list --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate location route

```text
OVERVIEW: Simulate movement along waypoints

Simulate the device moving along a route defined by waypoints. The device will
move between waypoints at the specified speed.

USAGE: devicectl device simulate location route --device <uuid|ecid|serial_number|udid|name|dns_name> [--route-file <route-file>] [--mode <mode>] [--distance <distance>] [--interval <interval>] [--speed <speed>] [--waypoints <waypoints> ...] [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --route-file <route-file>
                          Path to a JSON file containing route configuration
        Load route configuration from a JSON file instead of specifying
        arguments individually. When this option is provided, all other route
        options are ignored.

        JSON file format:
        {
          "mode": "distance",
          "distance": 100.0,
          "speed": 5.0,
          "waypoints": [
            {"latitude": 37.7749, "longitude": -122.4194},
            {"latitude": 40.7128, "longitude": -74.0060}
          ]
        }

        For interval mode, use:
        {
          "mode": "interval",
          "interval": 2.0,
          "speed": 5.0,
          "waypoints": [...]
        }

        Fields:
        - mode: Either "distance" or "interval"
        - distance: (Required for distance mode) Meters between location
        updates
        - interval: (Required for interval mode) Seconds between location
        updates
        - speed: Movement speed in meters per second
        - waypoints: Array of latitude/longitude coordinate objects
  --mode <mode>           The simulation mode
        Either 'distance' (update after traveling N meters) or 'interval'
        (update after N seconds).
  --distance <distance>   The distance in meters between location updates (for
                          distance mode)
        When using distance mode, the location will update after the device has
        traveled this many meters.
  --interval <interval>   The time interval in seconds between location updates
                          (for interval mode)
        When using interval mode, the location will update every N seconds.
  --speed <speed>         The speed of movement in meters per second
        The simulated speed at which the device moves between waypoints.
  --waypoints <waypoints> The waypoints as latitude,longitude pairs
        Provide waypoints as space-separated lat,lng pairs (e.g.,
        '37.7749,-122.4194 40.7128,-74.0060').

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate location scenario

```text
OVERVIEW: Set location using a pre-defined scenario or from a file

Set the device location to a pre-defined scenario or from a scenario file. Use
the 'list' command to see available scenarios.

USAGE: devicectl device simulate location scenario --device <uuid|ecid|serial_number|udid|name|dns_name> <scenario-name-or-file> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <scenario-name-or-file> The name of the scenario or path to a scenario file
        Either specify a scenario name from the available pre-defined
        scenarios, or provide a path to a file inside of the simulator runtime
        that contains the location scenario.  Use the 'list' command to see
        available scenarios.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate statusBar clear

```text
OVERVIEW: Clear any active status bar overrides

Remove all status bar overrides and return the device to displaying its actual
status indicators.

USAGE: devicectl device simulate statusBar clear --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate statusBar override

```text
OVERVIEW: Override status bar indicators with custom values

Customize the appearance of the device's status bar by overriding individual
indicators. You can set time, network status, signal strength, and battery
information. All overrides are cosmetic and do not affect the actual device
state.

USAGE: devicectl device simulate statusBar override [<options>] --device <uuid|ecid|serial_number|udid|name|dns_name>

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  --time <time>           Time to display in the status bar
        The time string to show (e.g., '9:41').
  --data-network <data-network>
                          Data network type to display
        Available values: hide, wifi, hotspot, 1x, GPRS, Edge, UMTS, 4G, LTE,
        LTEA, LTEPlus, 5G, 5GPlus, 5GUWB, 5GUC
  --wifi-mode <wifi-mode> WiFi connection mode
        Available values: notSupported, searching, failed, active
        If set to 'active', also specify --wifi-strength.
  --wifi-strength <wifi-strength>
                          WiFi signal strength in bars (1-3)
        Only valid when --wifi-mode is set to 'active'.
  --cellular-mode <cellular-mode>
                          Cellular connection mode
        Available values: notSupported, searching, failed, active
        If set to 'active', also specify --cellular-strength.
  --cellular-strength <cellular-strength>
                          Cellular signal strength in bars (1-5)
        Only valid when --cellular-mode is set to 'active'.
  --battery-state <battery-state>
                          Battery state
        Available values: draining, charging, charged
  --battery-level <battery-level>
                          Battery level percentage (0-100)
        The battery percentage to display.
  --battery-failing-to-charge
                          Show 'Not Charging' indicator
        Indicates the device is connected to power but not charging.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate statusBar preset

```text
OVERVIEW: Apply a preset status bar configuration

Apply a pre-configured status bar setup for common scenarios like screenshots
or testing different states.

USAGE: devicectl device simulate statusBar preset --device <uuid|ecid|serial_number|udid|name|dns_name> <preset-name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

COMMAND OPTIONS:
  <preset-name>           The preset configuration to apply
        Available presets:
        - screenshot: 9:41 time, full battery, strong signals (classic Apple
        screenshot setup)
        - low-battery: 5% battery draining with weak signals
        - no-service: No cellular or WiFi connectivity
        - charging: 50% battery charging with moderate signals

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```

###### devicectl device simulate statusBar show

```text
OVERVIEW: Show currently active status bar overrides

Display the current status bar configuration that has been applied to the
device. If no overrides are active, all fields will be empty.

USAGE: devicectl device simulate statusBar show --device <uuid|ecid|serial_number|udid|name|dns_name> [--verbose] [--quiet] [--timeout <seconds>] [--json-output <path>] [--log-output <path>]

DEVICE OPTIONS:
  -d, --device <uuid|ecid|serial_number|udid|name|dns_name>
                          The identifier, ECID, serial number, UDID,
                          user-provided name, or DNS name of the device.

OUTPUT OPTIONS:
  -v, --verbose           If given, provide more logging output than normal.
  -q, --quiet             If given, output will include only errors.
  -t, --timeout <seconds> The overall command timeout in seconds. If this limit
                          is exceeded the command is abandoned as a failure.
  -j, --json-output <path>
                          An optional path to write a JSON file with command
                          results. Pass '-' (or '/dev/stdout' / '/dev/fd/1') to
                          write the JSON to stdout instead of a file.
        For a file path, both absolute and working-directory-relative forms are
        accepted; existing files are overwritten. Any of '-', '/dev/stdout',
        and '/dev/fd/1' selects stdout. When the JSON document is on stdout,
        human-readable output (progress, status, log lines) is routed to stderr
        instead. A few commands write non-JSON content to stdout themselves
        (binary payloads, bridged remote stdout, legal notices) and will reject
        stdout-selecting values at validation time — see each command's help
        for details.
  -l, --log-output <path> An optional path to write all logging otherwise
                          passed to stdout/stderr.

OPTIONS:
  --version               Show the version.
  -h, --help              Show help information.
```
