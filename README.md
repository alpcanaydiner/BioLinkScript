# BioLinkScript
Sosyal medyada link havuzu oluşturmak için.


#
manifest.json içindeki başlıkları değiştirin 

js/ main.js https://i.hizliresim.com/nt92kh6.png sizin logonuz bu linki kendi logonuza göre ayarlaya bilirsiniz 

Ayrıca 

function share() {
	try {
		if (navigator.share) {
			navigator.share({
				title: 'Ap Yazılım  | Sosyal Ağlar',
				url: 'https://link.apyazilim.com.tr/'
			});

			console.info('Bağlantıyı başarıyla paylaştınız!');
		} else {
			alert('Tarayıcınız Web Paylaşım API"sini desteklemiyor!');
		};
	} catch (error) {
		console.error(`Web paylaşım API'sini kullanırken bir hata oluştu!\nError: ${error}`);
	};
};

bu kodlarıda kendinize göre düzenleyin 

index.php <head> </head> içindeki kodlara göz atın ve kendinize özel olarak düzenleyin 

youtube şarkısında sadece bu kısmı değişmeniz yeterli olacaktır  : https://www.youtube.com/embed/ (FfUmdamEros?si=-3IxEee44kabmVWy)

css/style.css içinde ise görsel düzenlemeleri yapa bilirsiniz. 
