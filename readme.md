# Proximal Policy Gradient (PPO) with PyTorch Using CleanRL Implementation

### Installation

```bash
apt install python-opengl
apt install ffmpeg
apt install xvfb
pip install pyglet==1.5
pip install pyvirtualdisplay

pip install ipykernel
pip install xvfbwrapper
# for mac need to install https://www.xquartz.org/
```

```bash
pip install gym==0.21
pip install imageio-ffmpeg
# for mac imageio
pip install huggingface_hub
pip install box2d
# for mac brew install swig
pip install wasabi

pip install wandb
pip install tensorboard
pip install python-dotenv
pip install box2d-kengz
pip3 install PyOpenGL
pip install pyglet
#for mac m1 pip install --upgrade git+http://github.com/pyglet/pyglet@pyglet-1.5-maintenance
```

```'
wandb login
python ./src/ppo.py --env-id="LunarLander-v2" --total-timesteps=50000
```
