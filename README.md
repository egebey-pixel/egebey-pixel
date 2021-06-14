- 👋 Hi, I’m @egebey-pixel
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
egebey-pixel/egebey-pixel is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
//---Bu Kod bot.js ye atılacaktır. 
//###CodeMareFi tarafından hazırlanmıştır - - - Ekleyen //###MareFi

client.on("message", message => {
    const kufur = ["sg","oç","oçe","anan","ananı","ananı sikim","anneni sikim","anneni sikeyim","ananı sikeyim","annen","ağzına","ağzına sıçim","ağzına sıçayım","ağzına s","am","ambiti","amını","amını s","amcık","amcik","amcığını","amciğini","amcığını","amcığını s","amck","amckskm","amcuk","amına","amına k","amınakoyim","amına s","amunu","amını","amın oğlu","amın o","amınoğlu","amk","aq","amnskm","anaskm","ananskm","amkafa","amk çocuğu","amk oç","piç","amk ç","amlar","amcıklar","amq","amındaki","amnskm","ananı","anan","ananın am","ananızın","aneni","aneni s","annen","anen","ananın dölü","sperm","döl","anasının am","anası orospu","orospu","orosp,","kahpe","kahbe","kahße","ayklarmalrmsikerim","ananı avradını","avrat","avradını","avradını s","babanı","babanı s","babanın amk","annenin amk","ananın amk","bacı","bacını s","babası pezevenk","pezevenk","pezeveng","kaşar","a.q","a.q.","bitch","çük","yarrak","am","cibiliyetini","bokbok","bombok","dallama","göt","götünü s","ebenin","ebeni","ecdadını","gavat","gavad","ebeni","ebe","fahişe","sürtük","fuck","gotten","götten","göt","gtveren","gttn","gtnde","gtn","hassiktir","hasiktir","hsktr","haysiyetsiz","ibne","ibine","ipne","kaltık","kancık","kevaşe","kevase","kodumun","orosbu","fucker","penis","pic","porno","sex","sikiş","s1kerim","s1k","puşt","sakso","sik","skcm","siktir","sktr","skecem","skeym","slaleni","sokam","sokuş","sokarım","sokarm","sokaym","şerefsiz","şrfsz","sürtük","taşak","taşşak","tasak","tipini s","yarram","yararmorospunun","yarramın başı","yarramınbaşı","yarraminbasi","yrrk","zikeyim","zikik","zkym"];
    if (kufur.some(word => message.content.includes(word)) ) {
        message.reply("Küfürlü & Argolu kelimeler kullanma! :face_with_symbols_over_mouth:")
        message.delete()
    }
});
