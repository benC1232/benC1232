# Hi, I'm Ben 👋

I'm a software engineer focused on C++ and Python. At work I get computer-vision models running on small edge devices. Outside work I like building things that run on real hardware, like an LED sign that shows live bus arrivals, plus a [weather provider](https://github.com/benC1232/weather-provider) that draws weather and rain-radar panels for it.

I'm looking for a full-time software engineering role.

![Skills](https://skillicons.dev/icons?i=cpp,c,py,go,kotlin,linux,docker,cmake,raspberrypi,githubactions)

## Projects

- **[sign-server](https://github.com/benC1232/sign-server) + [sign-code](https://github.com/benC1232/sign-code)**: a 128×32 LED sign on DIY [TransitTracker](https://transit-tracker.eastsideurbanism.org/) hardware that shows live bus arrivals and the weather. A Raspberry Pi holds the screen and other services post panels or animations to it over HTTP. The sign itself (CircuitPython on an Adafruit MatrixPortal S3) just fetches frames and draws them. *Python, CircuitPython*
- **[weather-provider](https://github.com/benC1232/weather-provider)**: the sign's weather panels. It shows temperature and humidity from the nearest Israel Meteorological Service station, an animated rain-radar scope built from IMS radar images in the rain season, and heat stress and UV in summer. Open-Meteo is the fallback. A first-run setup works out the sources and radar layout for your location. It runs in Docker or under systemd. *Python, Pillow, Docker*
- **[Cconnect](https://github.com/benC1232/Cconnect)**: an Android app for starting and managing Claude Code Remote Control sessions on my own machines over SSH. Pick a folder over SFTP and tap Start. Each session runs in tmux, so it survives disconnects. GitHub Actions builds the signed release APKs. *Kotlin*
- **[onionchat](https://github.com/benC1232/onionchat)**: an onion-routing network, my Magshimim final project. The server is C++ with SQLite, the relay nodes are Go, and the client is Python. *C++, Go, Python*
- **[trivia_2022](https://github.com/benC1232/trivia_2022)**: a client–server trivia game from Magshimim's advanced programming course. C++ server with SQLite, C# (WPF) client. *C++, C#*

Also: [cobalt-bot](https://github.com/benC1232/cobalt-bot), Discord and Telegram bots that re-upload media from links using [cobalt](https://github.com/imputnet/cobalt).
