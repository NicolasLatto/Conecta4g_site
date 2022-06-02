{
  "Version": "1.0.0",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "BOTAR LINK DA ATUALIZAÇÃO AQUI",
  "Sms": "BOTAR LINK DO SMS AQUI",
  "EmailFeedback": "apolossh@gmail.com",
  "UrlContato": "https://t.me/apolo_vx",
  "UrlTermos": "https://kiritosshxd.github.io/Conecta4g_site/termos.html",
  "CheckUser": "true",
  "FormatCheck": "yyyymmdd",
  "Udp": [
    {
      "Porta": "7300"
    }
  ],
  "Servers": [
    {
      "Name": "Servidor DG BR",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "gold.superapolo.xyz",
      "CheckUser": "http://209.14.71.214:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
    {
      "Name": "💙VIVO VÍDEO [SSL 1]",
      "FLAG": "vivo",
      "Payload": "GET wss://portaljud.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "portaljud.vivo.com.br",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💙TIM [SSL 1]",
      "FLAG": "tim",
      "Payload": "GET wss://cdnjs.cloudflare.com  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "cdnjs.cloudflare.com",
      "TlsIP": "104.16.19.94",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💙TIM [SSL 2]",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "static.r4you.co",
      "TlsIP": "104.26.5.175",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "💙TIM [SSL 3]",
      "FLAG": "tim",
      "Payload": "GET ws://emartim.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "emartim.com.br",
      "TlsIP": "104.21.27.243",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "💙TIM [SSL 4]",
      "FLAG": "tim",
      "Payload": "GET ws://cutim.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "cutim.com.br",
      "TlsIP": "104.21.4.149",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "💙TIM [SSL 5]",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.51.111",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💚VIVO [DIRECT 1]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.7.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "💚VIVO [DIRECT 2]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "vigia.vivo.com.br",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "💚VIVO [SSL 1]",
      "FLAG": "vivo",
      "Payload": "GET wss://money-staging.infinitepay.io/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "money-staging.infinitepay.io",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💚VIVO [SSL 2]",
      "FLAG": "vivo",
      "Payload": "GET wss://carrinho-pos-familia.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "carrinho-pos-familia.vivo.com.br",
      "TlsIP": "104.18.6.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "💚VIVO [SSL 3]",
      "FLAG": "vivo",
      "Payload": "GET wss://portaljud.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "portaljud.vivo.com.br",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "❤️CLARO [SSL 1]",
      "FLAG": "claro",
      "Payload": "GET wss://atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "atendimento.descomplica.com.br",
      "TlsIP": "no.descomplica.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "❤️CLARO [SSL 2]",
      "FLAG": "claro",
      "Payload": "GET wss://atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "atendimento.descomplica.com.br",
      "TlsIP": "714341g41.secure0121.hubspot.net",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "❤️CLARO [SSL 3]",
      "FLAG": "claro",
      "Payload": "GET wss://atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "atendimento.descomplica.com.br",
      "TlsIP": "199.60.103.228",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "💛OI [SSL 1]",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "www.hbogo.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "💛OI [SSL 2]",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.53.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    }
  ]
}
