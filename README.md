You can submit this job to IBM Cloud using ibmcloud cli.

First, edit the pytorch-train.yaml file with the corresponding values for object store.

Second, submit the job using: `ibmcloud ml train pytorch-mnist.zip pytorch-train.yaml `

Third, check the progress: `ibmcloud ml monitor training-runs model-<id>`
