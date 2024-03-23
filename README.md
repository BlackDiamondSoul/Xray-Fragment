# Xray-Fragment
Vpn canfig
برای استفاده از این fragment باید اول Termux نصب کنید
بعد منبع رو با استفاده از git clone دانلود کنید
بعد از اتمام دانلود برای نصب و راه اندازی دستور :
bash /data/data/com.termux/files/home/Xray-Fragment/xy.sh
وارد کنید

    uuid=$(~/xy-fragment/xray uuid)

    echo -e "${purple}Select a Config: ${rest}"
    echo -e "${green}1) socks${rest}"
    echo -e "${green}2) vmess${rest}"
    echo -e "${green}3) vless${rest}"
    echo -e "${yellow}select socks for Irancell${rest}"
    read -p "Enter the number of Config [1/2/3]. Default: 2 : " choice


    config-vless
        echo -e "${blue}--------------------------------------${rest}"
        vless_url="vless://$uuid@127.0.0.1:$port/?type=tcp&encryption=none#Peyman%20YouTube%20%26%20X"
        echo -e "${yellow}$vless_url${rest}"
        echo -e "${blue}--------------------------------------${rest}"
        echo -e "${green}Copy the config and go back to the main Menu${rest}"
        echo -e "${green}and select Run VPN [ Exclude Termux in Your Client [Nekobox] ${rest}"
        echo "$vless_url" > ~/xy-fragment/vless-tcp.txt
        
    در این صفحه نوع canfig انتخاب کنید 
    
    
    بعد میزان پورت رو نسبت به اعداد وارد کنید
    بعد از کپی کانفیگ و جاگذاریش در اپ nekobox یا ... به ترموکس برگردید و دستور bash رو دوباره بدید ولی اینبار گزینه با زدن عدد 2 گزینه run رو انتخاب کنید
    برید وی پی ان رو روشن کنید و استفاده کنید
    این Fragment رو بتده از petchgithub برداشتم تشکر میکنم از آقا پیمان گل
