# osxvpncli

This is a wrapper to help you start and stop your OS X VPN connections from the command line.

# Setup

Before you can do anything, you must first create the VPN connections that you wish to manipulate though "System Preferences -> Network".

If you would like working tab-completion, you can use the completion script in `bash_completion.d/vpn`. If you're not sure how to use bash_completion scripts, take a look at [this blog post](http://blog.jeffterrace.com/2012/09/bash-completion-for-mac-os-x.html).

# Usage

    USAGE:
      vpn [OPTION] <vpn_name>

    OPTIONS:
      connect         Establish a connection to a VPN
      disconnect      Disconnect an established connection
      status          Show the status of each of your VPN connections
