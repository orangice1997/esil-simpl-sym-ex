# esil-simpl-sym-ex

Work in progress
Exception:
Traceback (most recent call last):
  File "/usr/lib/python2.7/dist-packages/pip/basecommand.py", line 122, in main
    status = self.run(options, args)
  File "/usr/lib/python2.7/dist-packages/pip/commands/install.py", line 269, in run
    InstallRequirement.from_line(name, None))
  File "/usr/lib/python2.7/dist-packages/pip/req.py", line 173, in from_line
    return cls(req, comes_from, url=url, prereleases=prereleases)
  File "/usr/lib/python2.7/dist-packages/pip/req.py", line 71, in __init__
    req = pkg_resources.Requirement.parse(req)
  File "/usr/lib/python2.7/dist-packages/pkg_resources.py", line 2798, in parse
    raise ValueError("No requirements found", s)
ValueError: ('No requirements found', '# esil-simpl-sym-ex')

Storing debug log for failure in /home/user/.pip/pip.log
