<div align="center">
<img src="https://really.is-a.dev/res/media/emoji.png" height="150em" align="center">
<h1>really.is-a.dev</h1>
<p><a href="https://really.is-a.dev">really.is-a.dev</a> is a free nested sub-sub-domain service stemming from <a href="https://is-a.dev">is-a.dev</a>!</p>
</div>

<h2>Issues</h2>

If you have any problems, feel free to <a href="https://github.com/really-is-a-dev/register/issues/new/choose">open an issue</a>, send an email at <a href="mailto:really.is-a.dev@ukriu.com">really.is-a.dev@ukriu.com</a> or message <a href="https://ukriu.com/?socials">@ukriu</a>

<h2>Register</h2>

1. Fork the repo.
2. Make a json file named `example.json` in the `domains` directory.
3. Add the following file format to the json you just made:
```json
{
    "description": "Your Project Description",
    "owner": {
        "username": "yourgithubusername",
        "email": "hello@example.com",
        "repo": "yourrepohere"
    },

    "record": {
        "A": ["1.1.1.1", "1.0.0.1"],
        "AAAA": ["2606:4700:4700::1111", "2606:4700:4700::1001"],
        "CNAME": "example.com",
        "MX": ["mx1.example.com", "mx2.example.com"],
        "TXT": ["example_verification=1234567890"],
        "NS": ["ns1.example.com", "ns2.example.com"],
        "SRV": [
            { "priority": 10, "weight": 60, "port": 5060, "target": "sipserver.example.com" },
            { "priority": 20, "weight": 10, "port": 5061, "target": "sipbackup.example.com" }
        ]
    },

    "proxied": true
}
```
> [!NOTE]
> Only select the records you need, this is just a example on what all the records we support should be.

4. Make a Pull Request to the repo and wait for it to be merged. This may take a few seconds to a few hours to a few days.
5. After the Pull Request is merged, DNS should propogate in a moment or 24 hours.
6. That's all, enjoy your `really.is-a.dev` sub-sub-domain!

<h3>Credits</h3>

This subdomain was granted entirely by [is-a.dev](https://github.com/is-a-dev/register) and this project is really just a big joke.<br>This wonderful code for the `register` repository was entirely copied from [is-not.cool](https://github.com/is-not-cool/registration). Thanks troll8m and CuteDog! :P

<h3>Similar Services</h3>

If you want to find services similar to `really.is-a.dev`, please check out [is-not.cool](https://github.com/is-not-cool/registration) and [is-a.dev](https://github.com/is-a-dev/register).
