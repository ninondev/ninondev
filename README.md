I build apps and small tools, mostly because I want to use them myself. Coding agents write the code.

- [Dayside](https://github.com/ninondev/Dayside) is a world clock for the Mac menu bar. Each city gets its own row, colored to match the sky there at that moment. Version 1.0.1 is notarized, supports 16 languages, and has no network-access entitlement in its release build.

- [stove](https://github.com/ninondev/stove) prints kitchen tickets and manages a numbered order queue. I took this code from a POS system (Zaotai) I made for a restaurant, where hired staff used the system regularly from August to early October 2026.

- [dryport](https://github.com/ninondev/dryport) is an experiment in running Windows-only games on Apple silicon Macs. For Unity games, it translates D3D11 shaders into Metal instead of relying on Wine. *A Space for the Unbound* passed all five of my checks on an M5 Mac.

- [verbatim-quote](https://github.com/ninondev/verbatim-quote) checks whether a quote actually appears in its original source, character by character. In one test, changing just one number still left a similarity score of 0.96, but my tool found the mistake.

- [SpeakFB](https://github.com/ninondev/speakfb) helps me practice spoken English. It analyzes my recordings and shows my speaking speed, long pauses, and filler words. Transcription runs locally on the Mac.

I trained a 149-million-parameter model to score English exam essays using only a base-model MacBook Air. I finished it in August 2026, roughly 3 weeks before TypeSafe released Jev. Like Jev, my model predicted scores on an ordered scale instead of generating text, but it was limited to one type of essay. I tested it on 84 essays scored by people. Its predictions were within one scoring band of the human scores 88% of the time. I was aiming for 94%, so I didn't reach my goal. I later deleted the project.

My developer tools use the MIT license. My apps use GPL-3.0, along with a short contributor license agreement (CLA) that allows me to offer alternative licensing terms in the future.


Email: hola@ninon.dev
