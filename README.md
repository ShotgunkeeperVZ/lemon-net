# lemon-net
A Collection of tools to make life with bad Internet bearable. These are mostly focused on ML workflows but you can easily change them to suit your needs. Each Jupyter notebook is designed to leverage Google Colabs processing power and a stable internet connection to solve a specific problem.

## What's with the name?
The name stems from the fact that I just lost a good opportunity and hours of work to a shoddy internet connection. This is me trying to make a lemon-net out of lemons. You can learn more about my basket of lemons and the lemon factory I live in [here](other_file.md).

## How Does it Work?
Each notebook runs on Google Colab and may use services like Mega to permanently store data. Where needed you will be asked to provide your own API keys.

## Why use lemon-net?
If your internet connection is faster than **50Mb/s** and Indiana Jones is not actively trying to cut your connection with a sword, you don't need this!

As for the rest of us:
- **Backup:** If you are running your workload on an environment like Google Colab or a Kaggle notebook or any similar service, Downloading GbBs of data (which can take hours if you are lucky enough that your connection doesn't cut out every 10-15 minutes) to keep as a backup, doesn't make any sense. But by using services like Mega you can easily have copies of things like model checkpoints, without needing to download and upload a big file every time.

- **Cloud-Based Services:** A tool like Roboflow can be very useful but if downloading a big dataset takes several hours, it becomes impractical to use. On the other hand, if you instead download and preprocess the data in the cloud and then upload the results to a service like that from the cloud, you can use it without being slowed down by your connection.

## How to use it?
All notebooks are saved in the notebooks folder and their names describe what they do. Simply open them in Google Colab, follow the guide, provide the necessary inputs and run.
:triangular_flag_on_post: **Beware:** every tool is designed to be as not destructive as possible but regardless, **Do not use any of these tools with your main account or an account with valuable data**. There could be a risk of permanently losing data, especially when modifying the code. The best practice is to create a new account for each service involved. If a tool does delete any data it will prompt you to confirm at least for the first time in each session.
