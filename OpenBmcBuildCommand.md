
openBmc Build command:

mkdir asus_openbmc
cd asus_openbmc
git clone ssh://git@cicd-server-02:8822/dev/bmc/oprojects/asus_obmc.git
cd asus_openbmc
./obmc_builder setup x4tf 
./obmc_builder rebuild


git clone -b obmc-2.17 ssh://git@cicd-server-02:8822/dev/bmc/oprojects/asus_obmc.git
