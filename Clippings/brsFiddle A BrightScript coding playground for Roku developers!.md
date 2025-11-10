---
title: "brsFiddle: A BrightScript coding playground for Roku developers!"
source: "https://www.reddit.com/r/RokuDev/comments/11yu5dm/brsfiddle_a_brightscript_coding_playground_for/"
author:
  - "[[lvcabral]]"
published: 2023-03-22
created: 2025-11-10
description:
tags:
  - "clippings"
---
Hi fellow Roku developers, I’m happy to announce a new free tool that I just published, This is [brsFiddle.net](https://brsfiddle.net/) a BrightScript flavor of the popular [jsFiddle.net](http://jsfiddle.net/), a coding playground for testing and sharing simple code snippets in our beloved language!Of course it has the same limitations of my [BrightScript Emulator library](https://github.com/lvcabral/brs-emu), no SceneGraph (***yet***) and no Video Playback (***yet***), but it uses the brand new v0.10.21 library that is faster (thanks Mark Pearce for the help optimizing it) and now has implemented the ***Roku MicroDebugger*** so you can add break points (stop) to debug your code! Soon the web and desktop apps will also be updated with the new library!  Below a list of links with shared code examples for you to test the tool, enjoy and please let me know any issues or improvement suggestions:

- [Hello World](https://brsfiddle.net/?code=XQAAAALYAQAAAAAAAABJKocnAkqZmqFJVufERpNUvEumLE8r2F0pBn_ARViB86ec56VCTl3ARYZvpc88MDr3qKkOOc9f1Tql8GCXJogWpCmzW2mPuouTRKR-Fo7FTPo8hJ65P5coi0bvOTM9HKws6qVEsvjk5OdFSO1qlwa4UWGtMkVzEipOpO0MA8omlEqrr_hG6yrMGQ5GpCKfose7PfAhXy9kqCF7W6XEcr8o_c0mMCYohg0JRRam0w5dK3-9nmuerGUkEdPrKCJeFrIBwF5kDllsNX7o-jdWvrLbQgzPs4uC5E78nUm6uEq7-uVVNgQBSajAvJlN6Yc9YINPwJZN7sGy-TLqS3WYwXW4-dtPY8Djb2LIVHBCKptnyiXeIuntMazt753rNyeB_6gYQ14)
- [Rect Boing](https://brsfiddle.net/?code=XQAAAAIrEQAAAAAAAABJKocnAkqZmqFJVufERpQkf9KVk93fxmIRqnWDhwpkoNWGesOdd0NfqUQINBpHgpEwFE0OR1eAH7wa_jMdErSC0Ef6rWNCKA7QM7K-tYEah5tFpMmXnJglupGQccD85M9hTEo7RtutiOH7nQx0jpOyrhcPrtHzQA4-biFDUWkOLewpwh3KVNGdkIWlskO5MNh1rrex5e_N9S--J4xyUYV3ykTqocgnidX8ZYIFiQxb6J6GOW202zcXq8aWMgG-5R41nXEXigggzsTZXmLi13Xc6vsEVASb1mlaWHZlyAUU7hIhI-BvuJyDAEiWpmECFPSXVdLtdba-Hp4Q14J44MomrmpPXwI7ejX5PWKlW9TW7GdbI6kR1xTHv-SWNY7IulWCC_XXR1u11hlkAxkot6q7CUpuN3bJxWFyGL2WtiEu4htVubBbgZ4tcKR39TDePe9vNVkRbSwBDULMxlL4aHY7LxG6F4uiwj2UB1IjC7v3wQAtvIWpMN_U9Y5rJJlaPfZ5uAIN97HmQZ5Au3oonlSXGg2Edg2jPR3BG5Z8Bof_9-nR4YAa43N_w5HJWPnuLzsEITVY5svjES3ZroqUMyzwSW7dn3zdY_Gd24oWp4Ic3qWn5Fyjk-8Qw6ct4rK-q-mzkkF3rjXm5hUsWRKl_V_g7ESA51YmAlm0XWAWV6YyU3DcwGOKuE9fSYao2FzeUcDL-zYvI_AY7m34Mt5ZVQ0bu8x6vRnyMOs9bRQBLiiFw-Q-xJh0nka6Jtl-dC0me4MKeFfhCIWZq-2t78PPiPz-f2UZBZDerTi1jqJMFZ7rDrrJ0PSjPTi-t43qJ3Rrqi57AsyK7INo6wMFJZgPkcLkUcuDWjqD2QSEwJAFLyrdLWSkgl1PCCypEG0vHoDyqmGeWyCN5-TSb6ZgA51fln02CN-iBgm7cWNGaQ1--iwfd8n4gWVWzTh37_2J6buqPiNzsiDYdEVlRjeTocWiDx8ESYe7BbvLQ9AhqFWLWvzcc8EnH80gBimCK6-dJS58PtZrSmG_uVlpHP-UDAa67h0g5HHLP39mAh54zs5COmoRNqnIsTmFomDAUItoU7UI3djrTTp8ymEGwOzMi5qbLq6BCOs_LsasbT3eS132RnzpQ6eh_WdR-NjzijC9-LE6s4EeqwAueGMIvUJGnudHB7TcwemZ47vjsGTG14Y0p57VY1uzKGeJulkLJHi7VCWTV9a7ixdHxfPaRTwxYI1SGnS5DZEz65Hn1fMUjybGqJG1Rl_zuOcO9BeCBw0DF7gU7GbzwxaqGX3CV9RcCM0ggngxN50NgdKxOwSpSneI1t2AwY5FNlqnnvALfKqCOcP-xZgtgJeQyQg2a_h1wAZwOmX2evCM4k6JlqgCFCH0Ol_wz5ri4EyKhVzNFdtQdjLoprM0y9DAdRibs8LGsgwM3YKLezhCSK1O7Bz3udyCeIxBhx8aY8QeMB8nYqRFPARz5ulDGBDTnGB6wWW7UT3Hi5gj0No0ABIXsMot89yCR2EbE4FzAHM9kzn9sM7OfrmTOS2I1obIIbIPzI_HpnGGr2vAT7jyVqQlDis8Z8nwFastErVXG1sJYCoV7NYl78o_tXkwO73mZjxEDaFSDDuD5iFlIlYaAtN09Fs2sTev_DMJ3XkFBLeUcSUvSxEh2_dj5mYCVLSQ6T4ZJ5o7xRckRfHnZNpBrJ0lJT8K0PaQmwG1ZEXPgPjVk2_v4gIteee2W7Vwk0Jijy-hnN7y0q0lGlKkoke4vajaDl0ZWyNFWAo-KBYWXBnmzEkvapmWAI4qUZMP9a9unJpblNbYbHpmQzuKBTsX-H3GDWSsO6ePRuJJMiJGwSjYWdrbFIfKl5FZ7X66PwIcYvnzApikiIeB3TFef-BpQ2ea4QaaTmyselj4oISVVmL4TnAwKD0OCvH--kfPsX8f44VsGtA61fwmsbPZ3b2g_CFMe8AlhWI7fiKj4wfYA9k77fba1jPGuirRAQn_eSnsAA)
- [Rect Bounce](https://brsfiddle.net/?code=XQAAAAJLDAAAAAAAAABJKoIm03vhplbs8vAoV718lYQaq2iqIzD0wjMeWz0x2uLwDigINEmN4AAisssOVyUe5GZRzMIzPujx0W_8qLykUusZ21AhtV7HOD1TUFmqoEfXGPy25s1kX-58O0UmkqyEPdruUr9mF_zj4iceg7xTe5NjfsaLjyqRlG5HkZsPO4vBr9qKep2XIxWBFVwaXQvhMxNXWCTVF_jpyfUlaSfjeddhGpzG4QTfz6yCM1T0eyRmV0WUug5W7aMO-fCeefvaSaEEw2Z1OIxSR3DZs134DfxExTY__lK3zn3HYvgxQUxb-OvF7yrGGPGNxBbDpxfY4cltWA6rlMZ6NLQ4DFm3v0gVs9FzCctLXhpszC6DyhpWRh-4H_5XjoV2qkpmwIIZIjGyUynXZXufSW00xAQujuzuQ8sNjxUOXt1k5hqhqNj7VZVxNoeVz7JwknG8wMIxQKsbbMd-OJTNZ7BgObYxlaZ4EIUmy6AqgdEV0GdvoicnmJ1fnEFMYf7lfSmsIvttTEDxb8sTlxaJhfmhpPdnSoJQObo4p_nYCeMSgNJkLNX_tMpR4MbqlNrUp7j8bRitCyvX1rsNLoNxvF3lsNSRGg1g36QBvTOC0VinIKkQoDTNcX7eyPbReN8Coq_CBtRXWiiiaxj1v6w0KQB9Dhc3-0DtawYUlQKCEacMmvfTZ4nB-QejdfiowODOo2pKvh0bEa8ZPfMuELXZmZdDMVQnbc4LVgr48zfh-LOjEHCDC2tI1akPH1dBA5DscS74wVf9WzW88xe04u2nzytfFIeHO9Pxh5Zbfzv8ZrEa8xwSlWGrAgNLDst036Hcj7td0somS3BmzFYTlvvM9_kg3Z8ywUvq5e2r3mXk2Lb9ev0lHPrfbZFrkDwuTmzSwYZxIg40Q433RbDLzSe0glBc-dl6EP4IK3wy0y3Ga6irGOgYUTvs2JhyGs61Eza9fdVYwa7R_AKsKMfLKOdwh-lrP76JxBJNTNhpaqBnsxroYNeZWAMgFT3uz1ZabJCuPS7eSfPXOuIoV1kmtsCHp2lBU0yykWeT19ThSqHSM48VRrEMeS6JNO0Xl54adVl5V4e9r5yyOvwhtRwM1ZEnndBEPlb0F1CGI164CDayEWIcE9iDZl_-NoIi5hLmV6D4U-XqewPtqs4M6ZaUsAyNI6GEEUnHELHR6tfVQ77AqKF4fXC0JsLQK4Bolqec2Fv1gwKzcsejDHBbga5dI7C6n-76ucj8csqYhtw7vP-fi7s7N8gxo-N7V4sF5Nx_AuqIeNcHYFAyFAUjroa4iGgHIU0iwG3ykeapmfL4KbNQlMT-jUvNj4EjszZn-ZppVKyc93ewk4Anj_50pRw)
- [Text, Images and Mp3](https://brsfiddle.net/?code=XQAAAAJqCQAAAAAAAABJKoMnQ-exSUWPG3fpxfwVM0I3_ROH-bzVbB7Jp09rkgEHk97O65LMrkY-ClFix02OAL9aQHdA6uHMp6VomRlb0EzSG23ee59pGlwA2DbEVNpCpCimia_7ffBTl-0p010UxxlLTCoMZ9xkzc-ZK8hxFih-i3P-nRWSdi82_7NwrrNelSDuJOdHfV28SNUbhHOULHLQ7f1EwhvrFr_vgpoksK6d-YKwnX6XWlNIlZrwulg0tclDcoxtRQawghOcZ3oTzmLTy0FuSIagck0NdcmdD-GAqqynbbR7Pb0jhFa4IK7RBM2lcVTjoH69laKA_CBKux6zj3VYBGAnz2lXtkI6dRfT_1XRSN7zkxNIJke8HWFZbyM1uc8s_kq7oPdwYBpvtkEfdHc96hiWZQMRpbdNRFa0Bx_1Jy5k-krINqCIe9489ZrPaend2fS191EBMIaCrzqcBrkNULQET0GcYBPJ5rhnr0sFT_knv4sPfD2HlYLc5h8xOBTxNgR8ex5COmRiI0xnHEgZmWP6fWSktG-gWH9Fk3nYb5xxt8VDvQuAOoeFsyxfucaRl5R2t5jRGN5dX8ECIa3T-Z_M_RIRXr8fWvUmdIwftjlkRYYJw-Imqc0phOMyLJnDIZGEodUavAvT5L7GaI4Qn_hFmxxyHaeMZw2HnDZPshIWfjSxzkcfuJyzx-X8ZeBcEq3ppDLCWkGml-GOSUDbVRd-LvDmSOVEa652DRrwpYskvsXvVxOxo_nbMyJlCyuYdTM0tU0DIXSd6frNSLciud6YrGX0b0JcbLs-c7Fy_flud8htvUNKD4ugdOqZJTxUHi8cjV6nD9aT3v5yj_C99p4r5H-UhK7qrRii9mbQbhHkEMNi4Zb4DIfntBK8p2GIIeaP--Mvo02v8o6ZBj9CbyOM-jpv1SfhZ8tyfXcw_3KoT_VgbuDseShlzToWgbkyBa-SzJFklEZPGteuysyFRSPnmgfFOKTZTpY92mxcQ9C8TZXt6Gbwj79AbplH6d0wKPl_uQiGmXVzj9LvIsYhuY3o-Pr2ZfZGBo4O4sMuQQ5ZA892cRuvrp_XRRKSEunIhWqBIgoSxiI1yp46twsZy2SQXpVISxFdHDJaDHMdMX4VBO33Oy1I8zlfQGPrHQxik8Szk-s6qkOpgaQnNNaLcE1v8LHpRMXSP5KxfwJm6PyWkGQ)

PS. Try to pause the Rect Boing example and change the box color using the Micro Debugger, then run **cont** and see it continue to boing  with the new color

---

## Comments

> **PopTheKeckleOn** • [4 points](https://reddit.com/r/RokuDev/comments/11yu5dm/comment/jdantib/) •
> 
> Awesome work mate - always great seeing new Roku dev tools in the wild.

> **jawanda** • [3 points](https://reddit.com/r/RokuDev/comments/11yu5dm/comment/jdcqq58/) •
> 
> Very cool , thanks for sharing. Roku development can be a little intimidating nice to have a tool to practice brightsctipt in browser !

> **Objective\_List\_7452** • [2 points](https://reddit.com/r/RokuDev/comments/11yu5dm/comment/jrd374n/) •
> 
> Hello, first time doing this and of course suffering.... i want to intergrate my roku to show ring camera live feed. I DL everything, virtual machine, logged in via ip address to Home Assistant... I first tried to set an automation and of course it didnt work. Then i read that i have to "side load" the Home Assistant Cast App to the roku, and of course i cant seem to figure it out. I think i need to create a https, and i tried through duckdns but when i configure everything, i cant reconnect to the same ip address nor using the new domain. Can anyone help :(. Am i heading the correct way to "Side Load" the Home Assistant Cast app?

> **BigRonnieRon** • [2 points](https://reddit.com/r/RokuDev/comments/11yu5dm/comment/jsn0o8f/) •
> 
> Looks neat! Thanks!

> **lvcabral** • [1 points](https://reddit.com/r/RokuDev/comments/11yu5dm/comment/lx4luh7/) •
> 
> I just released v1.6.0 of [brsFiddle.net](http://brsfiddle.net/) that introduces a way to rename, save as, and export/import all code snippets! The tool is open source now for a few months you can check the release notes on the Github repository: [https://github.com/lvcabral/brs-fiddle/releases/](https://github.com/lvcabral/brs-fiddle/releases/)