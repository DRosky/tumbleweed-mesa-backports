# tumbleweed-mesa-backports (Intel UHD Graphics)
OpenSuSE Tumbleweed Mesa RPMs for Intel UHD Graphics built with inter-context synchronization backport patch.

Backport patch: https://gitlab.freedesktop.org/mesa/mesa/-/merge_requests/14783/diffs

See the Releases area for the package files.

Very lightly tested -- only on my machine.
Use at your own risk, no guarantees but they work on my system.

I suggest downloading and manually installing using rpm:

rpm -Uvh --force --test Mesa-gallium-21.3.4-298.2.x86_64.rpm Mesa-dri-21.3.4-298.2.x86_64.rpm

If that returns no errors then re-run the command without --test

