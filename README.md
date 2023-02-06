sam deploy -t packaged-template.yaml \
    --no-disable-rollback \
    --no-fail-on-empty-changeset \
    --image-repository 040536061213.dkr.ecr.ap-southeast-2.amazonaws.com/gayan-test \
    --parameter-overrides=Revision=latest

