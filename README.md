# tumbleweed-mesa-backports
OpenSuSE Tumbleweed Mesa RPMs built with inter-context synchronization backport patch.

Backport patch: https://gitlab.freedesktop.org/mesa/mesa/-/merge_requests/14783/diffs

See the binary releases

Very lightly tested -- only on my machine.
Use at your own risk, be able to recover.

I suggest downloading and manually installing using rpm:

rpm -Uvh --force --test Mesa-gallium-21.3.4-298.2.x86_64.rpm Mesa-dri-21.3.4-298.2.x86_64.rpm

If that returns no errors then re-run the command without --test

