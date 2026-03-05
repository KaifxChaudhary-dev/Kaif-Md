۔# Clone repository
git clone https://github.com/mrwasif-dev/Muzamil-MD.git

# Enter directory
cd Muzamil-MD

# Install dependencies
npm install

# Create .env file with your configuration
echo "SESSION_ID=sarfrazzz1" > .env
echo "MONGODB_URL=mongodb+srv://kaifxchaudhary_db_user:kaifxchaudhary_db_user@cluster0.sga7pef.mongodb.net/?appName=Cluster0" >> .env
echo "SOURCE_JIDS= 120363039886026840@g.us,
  447973702186-1372399425@g.us,
  120363179441396828@g.us
" >> .env
echo "TARGET_JIDS= 120363347012713784@g.us
120363314824127848@g.us >> .env

# Start the bot
npm start
