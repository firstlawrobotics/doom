Instructions for Google Cloud:

1. Get an account and the free pesos
2. Request to increase your limit of GPUs to 1 from 0. This will take them an hour, tops. They are magical and good folk.
3. Build a box according to these instructions: 
https://medium.com/google-cloud/jupyter-tensorflow-nvidia-gpu-docker-google-compute-engine-4a146f085f17
https://github.com/fluxcapacitor/pipeline/wiki/GCP-GPU-Tensorflow-Docker
4. sudo pip3 install gym
5. sudo pip3 install ppaquette-gym-doom
6. install vizdoom.. I think.
7. install cig2017
8. You don't have a monitor so there are some funkinesses to handle. So run "xvfb-run -s "-screen 0 1400x900x24" bash"
9. You will probably also run into some funkiness with loading everything. Before game.init() add game.add_game_args("+vid_forcesurface 1").


Random shouts to the ZDoom community, the ViZDoom community, mwydmuch, and ppaquette for making some great stuff.
