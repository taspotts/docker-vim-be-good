docker-vim-be-good
------------------

Allows users to play http://github.com/ThePrimeagen/vim-be-good without
installing or building anything.

`stable` image build steps:

- `docker build --no-cache -t taspotts/vim-be-good:stable stable`
- `docker push taspotts/vim-be-good:stable`

`latest` image build steps (uses `stable` as a base):

- `docker build --no-cache -t taspotts/vim-be-good:latest latest`
- `docker push taspotts/vim-be-good:latest`
