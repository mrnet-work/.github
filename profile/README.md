This organization is for the domain mrnet.work.

It is a collection of docker-compose.yml files to import within portainer to quickly bring services online.

Changes are made in the git repository, and webhooks trigger a change pulling in the new docker container with the changes.
###

Pull in repository

`git clone git@github.com:mrnet-work/.github.git`

`git submodule init`

`git submodule update --recursive --remote`


###
`
cd path/to/submodule
git pull origin main
cd ../..
`
##
`
git add path/to/submodule
git commit -m "Update submodule(s)"
git push origin [branch-name]
`
