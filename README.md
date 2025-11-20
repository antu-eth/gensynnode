🖥️ Gensyn-ai-Rl-Swarm_Guide {Linux}

-----------------------------------


Pre-Requirements 🛠


✅Install Python and Other Tools


1️⃣ sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof


2️⃣ python3 --version

----------------------------------------------------------------------------------------------

Install Node.js , npm & yarn 🤖


1️⃣ curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && sudo apt update && sudo apt install -y nodejs

✅Install Yarn (linux)

2️⃣ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

3️⃣ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list > /dev/null

4️⃣ sudo apt update && sudo apt install -y yarn

Check version ✔️

node -v
npm -v
yarn -v

---------------------------------------------------------------------------------------------------------

Start The Node 🎬



1️⃣ Clone RL-SWARM Repo

git clone https://github.com/gensyn-ai/rl-swarm.git

2️⃣ Navigate to rl-swarm

cd rl-swarm

3️⃣ Create & Activate a Virtual Environment

python3 -m venv .venv
source .venv/bin/activate

4️⃣ Run the swarm Node
./run_rl_swarm.sh

----------------------------------------------------------------------------------------------------------------------------
⚠️


Now it will promt you to login: http://localhost:3000/ enter your Gmail And Submit Code from Your Gmail

Now It will promt Would you like to push models you train in the RL swarm to the Hugging Face Hub? [y/N] Enter N

Now It will promt >> Enter the name of the model you want to use in huggingface repo/name format, or press [Enter] to use the default model. press Enter & get defalut model:

Now It will promt >> Would you like your model to participate in the AI Prediction Market? [Y/n] Enter Y


-------------------------------------------------------------------------------------------------------

⚠️ Save your swarm.pem file (for future login)




-----------------------------------------------------------------------------------------------------


⛩️ How To start the Next Day 
 
1️⃣ cd rl-swarm

2️⃣ python3 -m venv .venv
source .venv/bin/activate

3️⃣ ./run_rl_swarm.sh




------------------------------------------------------------------------------------------




🎉 You're All Set!

You now have a fully working Gensyn RL-Swarm Node running on Linux.
By staying online and active, you help strengthen decentralized AI compute and contribute directly to the future of open AI training.

If you found this guide helpful, feel free to:

⭐ Star the repository
📬 Share improvements or PRs
🐛 Open an issue if you face any errors
🚀 Stay connected with the Gensyn community

🙌 Contribution & Support

This guide will continue improving based on community feedback.
Pull Requests, optimizations, and new discoveries are always welcome.

For any support:

Join Gensyn community chats

Read the official docs

Or simply raise an issue here on GitHub

🔗 Keep Building. Keep Contributing.

Decentralized AI is the future — and you're helping build it.


-------------------------------------------------------------


✅ My Social Links

#️⃣ YouTube link:- https://www.youtube.com/@antu_eth

#️⃣ X (Twitter) link :- https://x.com/AnTu_eth

#️⃣ Discord User :- @antu_eth











