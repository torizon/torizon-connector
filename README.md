This is a project that allows Torizon Cloud to be used with
apt-based systems (Debian and Ubuntu).

Currently supported distributions: Debian {Stable (Trixie), Oldstable
(Bookworm)} and Ubuntu {Noble, Jammy}.

The script is tested against a fresh install of those distributions.

> [!WARNING]  
> Note that this script will permanently remove and install things in your system, so we do not recommend running it on development machines.
> Using a fresh, clean install, preferably that can be reset to a good and known state, is recommended for evaluating this solution.

To install, [create a Torizon Cloud account](https://app.torizon.io/run) and
run it as root (or with sudo):

```
sh -c "$(curl -sSL https://raw.githubusercontent.com/torizon/torizon-connector/main/install-torizon-connector.sh)"
```

Or

```
sudo sh -c "$(curl -sSL https://raw.githubusercontent.com/torizon/torizon-connector/main/install-torizon-connector.sh)"
```


The script will create a log file in `/tmp/install-torizon-plugin.log`.

Development happens on [GitLab](https://gitlab.com/toradex/rd/torizon-core/packages-and-containers/cloud-connector), this is a ready-only mirror.
