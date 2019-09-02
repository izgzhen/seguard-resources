# SeGuard public resources

## What is it?

SeGuard is a static analyzer framework for building semantic graphs of android malware.

## Quick start

Download `seguard-java.tar.gz` and `seguard-python.tar.gz` to current folder from https://github.com/uwplse/seguard-resources/releases. Install dependencies [specified here](https://izgzhen.github.io/seguard-www/quickstart.html).

```
# project root
mkdir seguard-framework

# install java artifact
mv seguard-java.tar.gz seguard-framework
cd seguard-framework
tar xvf seguard-java.tar.gz
cd ..

# install python artifact
tar xvf seguard-python.tar.gz
mv seguard-0.1dev seguard-framework/tools/python`
cd seguard-framework
virtualenv -p python3 .venv
source .venv/bin/activate
pip install -e tools/python

# try it
tools/seguard-cli examples/drebin0-5fd871.apk
```

## Onboarding for New Contributor

[ONBOARDING.md](ONBOARDING.md)

## Wiki

https://github.com/izgzhen/seguard-resources/wiki

(Edit as will)

## Blog Posts

- 2019-05-29: [Graph Representation in Malware Detection](https://github.com/izgzhen/seguard-resources/blob/master/posts/case-study-01.md)

## Video Tutorials

- [SeGuard error anlaysis](https://vimeo.com/350633606), [transcript](files/transcript/error-analysis-01.txt)

## Team

- Lead Developer: [Zhen Zhang](https://homes.cs.washington.edu/~zgzhen/)
- Contributors: [Luxi Wang](https://github.com/LuxiWang99), [Xiaxuan Gao](https://github.com/MarkGaox), [Andrew Shi](https://github.com/andrewshi98)
- Advisors: [Yu Feng](https://cs.ucsb.edu/people/faculty/feng), [Mike Ernst](https://homes.cs.washington.edu/~mernst/), [Isil Dillig](https://www.cs.utexas.edu/~isil/)
- Industry Collaborators: Sebastian (Google), Alec (Google)
