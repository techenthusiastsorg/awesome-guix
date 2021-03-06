# awesome-guix
List of awesome things and resources about GNU Guix (https://guix.gnu.org). Pull requests welcome.

## Official Documentation

- <https://guix.gnu.org/guix-refcard.pdf>

  _Reference card_

- <https://www.gnu.org/software/guile/manual/>

  _GNU Guix Manual_

- <https://guix.gnu.org/cookbook/>

  _GNU Guix Cookbook_

## Why Guix?

- Solving the deployment crisis with GNU Guix - Dave Thompson, Christopher Webber - LibrePlanet 2016 ([video](https://www.youtube.com/watch?v=iM3y9CSjMtI), [pdf](https://media.libreplanet.org/mgoblin_media/media_entries/1420/libreplanet_guix.pdf))

- <https://ambrevar.xyz/guix-advance/>

  _Guix: A most advanced operating system (and: A quick look at the history of operating systems)_

## Trying Guix

- <https://github.com/fanquake/core-review/blob/master/guix/vm-intro.md>

  _Bitcoin Core notes on how to run Guix in a QEMU virtual machine_

- <https://www.ubuntubuzz.com/2021/04/lets-try-guix.html>>

  _(Ade Malsasa Akbar, Ubuntubuzz) Let's Try Guix_

## Installing Guix and First Steps

- _Pjotr Prins Guix notes_
  - <https://github.com/pjotrp/guix-notes>
  - <https://gitlab.com/pjotrp/guix-notes>

- <https://gist.github.com/atweiden/c60d27357c182f0913d2>
  
  _Andy Weidenbaum Guix notes, 5 years old_

## Using Guix day-to-day

- <https://emacs-guix.gitlab.io/website/>

  _Emacs-Guix: Use Guix without leaving Emacs_

- <https://gist.github.com/peanutbutterandcrackers/844c211a91137c19607ae75b59fa116f>
  
  _(Guix-DE-Integration.md): A guide to better desktop environment integration for Gnu Guix_

- <https://www.draketo.de/software/guix-work.html>

  _(ArneBab): Using GNU Guix for software development (explains how to use Intellij, Zoom, npm...)_

## Going deeper with Guix

### Programming Guix

Scheme programming resources by ascending complexity and specificity to Guix

- <https://guix.gnu.org/cookbook/en/html_node/A-Scheme-Crash-Course.html>

  _Scheme Crash Course, from the Guix Cookbook_

- <http://www.starynkevitch.net/Basile/guile-tutorial-1.html>

  _A Guile/Scheme mini-tutorial for GNU/Linux developers_

- <https://people.eecs.berkeley.edu/~bh/ss-toc2.html> (book)

  _(Simply Scheme, 2/e © 1999 MIT): to learn scheme_

- <https://htdp.org/2003-09-26/Book/>

  _(How to Design Programs 1/e © 2001 Massachusetts Institute of Technology): to learn scheme, with DrScheme as IDE_

- Structure and Interpretation of Computer Programs, second edition, 2/e © 1996 MIT
  - <https://mitpress.mit.edu/sites/default/files/sicp/index.html> (book)
  - <https://www.youtube.com/playlist?list=PLE18841CABEA24090> (videos)
  - <https://sarabander.github.io/sicp/> (unofficial ebook)
  - `guix install sicp && info sicp` (texinfo)

  _To learn scheme also, the harder way._

- <https://www.gnu.org/software/guix/guix-gpce-20171023.pdf>

  _(Code Staging in GNU Guix): required reading to understand G-expressions (`#~`, `#$`, `#$@`)_

- <https://jeko.frama.io/>

  _(Guile Hacker Handbook)_

### Packaging for Guix

- <https://gist.github.com/Brainiarc7/0943ed4ac4d59b6648de>
  
  _(Set Guix hacking env.md): "Use this to set up a functional Guix hacking space. Useful when porting apps to GNU Guix.", 5 years old_

### Imaging with Guix

- <https://othacehe.org/the-guix-system-image-api.html>

  _Mathieu Othacehe. The Guix System image API_

### Deploying with Guix

- <https://guix.gnu.org/en/blog/2020/running-guix-system-on-a-linode-server>

  _Running Guix System on a Linode Server_

- <https://guix.gnu.org/en/blog/2020/running-a-ganeti-cluster-on-guix>

  _Running a Ganeti cluster on Guix_

## Troubleshooting

- [Fixing `warning: setlocale: LC_ALL: cannot change locale (en_US.utf8)`](https://www.reddit.com/r/GUIX/comments/jpq1uw/bashminimal507binbash_warning_setlocale_lc_all/)
