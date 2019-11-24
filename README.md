# CatGallery2k20

CatGallery2k20 is an information security challenge in the Web category, and was presented to participants of [KAF CTF 2019](https://ctf.kipodafterfree.com)

## Challenge story

Cool forum to share your cat photos. finally. #y2k20.

## Challenge exploit

RCE on php site to reveal 7Z password.

## Challenge solution

No need

## Building and installing

[Clone](https://github.com/NadavTasher/2019-CatGallery2k20/archive/master.zip) the repository, then type the following command to build the container:
```bash
docker build . -t catgallery
```

To run the challenge, execute the following command:
```bash
docker run --rm -d -p 1010:80 catgallery
```

## Usage

You may now access the challenge interface through your browser: `http://localhost:1010`

## Flag

Flag is:
```flagscript
KAF{3v3n_1F_Jz0n_i5_n007_prr3s3n7_i7_1z_7h3_8e5t_furrma7}
```

## License
[MIT License](https://choosealicense.com/licenses/mit/)