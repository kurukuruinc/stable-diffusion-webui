For face id ip adaptor need lora ip-adapter-faceid-plusv2_sd15_lora.safetensors
```
wget https://huggingface.co/h94/IP-Adapter-FaceID/resolve/main/ip-adapter-faceid-plusv2_sd15_lora.safetensors?download=true -O ip-adapter-faceid-plusv2_sd15_lora.safetensors
```

Different style:
```
wget https://huggingface.co/SG161222/Paragon_V1.0/resolve/main/Paragon_1.0_Beta-fp16-no-ema.safetensors?download=true -O ParagonNoVAE.safetensors
```

For use with face id (needs VAE):
```
wget https://huggingface.co/SG161222/Realistic_Vision_V5.1_noVAE/resolve/main/Realistic_Vision_V5.1_fp16-no-ema.safetensors?download=true -O RealisticVision5.safetensors
```

sudo pm2 start webui.sh
