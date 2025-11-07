## Hugging Face Login

**Author: Abhishek Dey**


### Create a dot env file and keep the hf-token

```

touch .env

copy hugging face token in .env file

```

```
HF_TOKEN_WRITE="hf_**************************"

```

### CLI Login

```
hf auth login

```

<p align="left">
<img src="images/1.png" width="800" height="480">
</p>



### Check the logged-in username

```
hf auth whoami

```

<p align="left">
<img src="images/2.png" width="800" height="160">
</p>



### CLI Logout

```

hf auth logout

```

<p align="left">
<img src="images/3.png" width="800" height="160">
</p>


### API Login

* Checkout [hf_api_login](hf_api_login.ipynb)

