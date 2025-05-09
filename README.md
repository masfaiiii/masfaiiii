<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Anniversary Sayaanggg 💖</title>
  <style>
    body {
      background-color: #fce4ec;
      font-family: 'Courier New', Courier, monospace;
      color: #880e4f;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      padding: 20px;
      text-align: center;
    }
    .typing {
      font-size: 14px;
      white-space: pre-wrap;
      border-right: 2px solid #880e4f;
      animation: caret 0.7s steps(1) infinite;
      max-width: 600px;
    }
    @keyframes caret {
      50% {
        border-color: transparent;
      }
    }
  </style>
</head>
<body>
  <div class="typing" id="typing"></div>

  <script>
    const text = `Assalamualaikum sayaanggg

happy anniversary 🥳🥳 1th
semogaa mimpii mimpii kitaa terwujudd kedepannyaa, aamiin
semogaa kitaa bisaa sukses bersamaa, aamiin
semogaa kitaa bisaa diberii kemudahan dalam menjalankan kehidupan, aamiin
semoga jugaa hubungann kitaa makinn langgeng dann eratt kedepannyaa hinggaa naikk ke pelaminan, AAMIINN
semogaa rezeki kitaa dilimpahkan agarr kitaa bisaa seringg bersedekahh, aamiin

gaa kerasaa yaaa udaaa 1 tahunn berlaluu, kitaa udaaa melaluii banyaakk hall dalamm 1 tahunn ke belakangg, kaloo di tarikk lagii, kitaaa inii kann awalnyaa sangatt amatt stranger, kitaa bahkaann gaa kenall darii siapaa siapaa, kitaa benerr benerr stranger yangg gaa adaa kaitann dann gaa kenall siapapunn, bahkaann berpacaran sampee setahun ajaaa ituu hall yangg akuu ga expect darii hubungan inii 😭 1-3 bulann awall akuu mikirr, \"ini bakalann samaa ajaa kykk kemarinn, gaa lebihh darii 5 bulann\" ternyataa, udaaa setahunn jirrr... siapaa sangkaa cobaa kitaa yangg sebelumnyaa cumann salingg likee di leo, teruss ceritaa\" randomm gajelass sampee benerr benerr jadian dann menjalani hubungan selamaa 1 tahunn, mungkinn akuu haruss berterimakasih samaa yangg bikinn Leo ituu siii, bisaa mempertemukann akuu dengann pacarkuu cantikkuu manisskuu sekarangg.

kaloo di pikirr pikirr banyaa rintangann yangg kitaa laluui darii 2024 sampee 2025 inii, banyakk kejadiann, dann amarah yangg kitaa keluarkan selamaa setahunn inii, tapii yangg bikinn kerennyaa, kitaa bisaa melewatii ituu semuaa hinggaa titikk inii, banyaa perjuangann dann waktuu yangg terbuangg, i really really proud of u, akuu banggaa samaa kamuu, dann akuu banggaa bisaa jadii bagiann darii kisahh kamuu dann berperann sebagaii pasangann kamuu, 
makaasii sayaangg, kamuu selaluu ngeapresiasi akuu, selaluu kasii akuu kebahagiaan yang orang lainn belomm tentuu ngerasainn kebahagiaan ku inii tapii kadang jugaa akuu ga sadarr tentangg perlakuan kamuu ke akuu yangg begituu luarbiasaa, maaff belomm bisaa jadii pasangann yangg sempurnaa sejauhh inii. Kitaa pastii salingg berfikirr untukk selaluu buatt pasangann kitaa bahagiaa dengann keberadaan kitaa, Kitaa jugaa pastii berfikir jikaa/misall pasangann kitaa melakukan hall yangg ga kitaa sukaa (bagaimana ya?) mungkinn kamuu kaloo berfikirr diemm², kamuu ngerasaa belomm berkontribusi apaa apaa terhadap hubungan inii, kamuu salahh besarr sayaangg, kontribusi kitaa samaa samaa besarr, kitaa adalahh hubungannn yangg benerr benerr setaraa, semuaa yangg kitaa lakukann setaraa, kontribusi, effort yangg kamuu kasii ke akuu, sudaa lebii darii cukupp sayaangg, soo kaloo misall kamuu berfikirr seperti ituu, jangann mikirr gituu lagii okaaayy?? semuaaa yangg kitaa lakukann, ituuu setaraaa

yangg akuu harapkann untukk hubungann kitaaa kedepannyaa, akuu cumann mauu hubungann kitaa seperti inii ajaaa, yaaaa mungkinn bisaa dengann beberapa variasii, mungkinn bisaa sii balikk kykk awall\" pacarann seruu tuhh 😭 gaa adaa yangg akuu harapkann lebihh untukk hubungann inii kedepannyaa, akuu cumann mauu hubungann kitaa seperti biasanyaa, karenaa hubungan seseorang tidakk bisaa mengikuti standar orangg lainn, semuaa hubungan punyaa porsii dann tipee hubungan masingg masingg, mengikuti trend mungkinn jugaa bisaa dibilang idee baguss, cumann kitaa bisaa selektif lagii kedepannyaa, trend manaa yangg baikk dann burukk, soo intinyaa akuu hanyaa inginn teruss jadii pasangann kamuu, akuu inginn teruss berhubung seperti inii dann mungkinn gituu ajaa sii

kaloo ditanyaa banggaa nyaa punyaaa kamuu ituuu, takk terhinggaa (seriuss ga too much inii)
akuu benerr benerr banggaa samaa kamuu
wanitaa yangg cantikk, imuttt, lucuuu, wangii.
kamuu memiliki pribadii yangg positif vibes, yangg bikinn akuu klepek-klepek samaa kamuu, kamuu ituu bukann tipee yangg mintaa inii ituu inii ituu😓kamuu cumann lihaatt dann bilangg kaloo pinginn, tapii kamuu gapernaa nuntutt akuu buatt inii ituu inii ituu, bahkann kamuu gapernaa mengeluhkan apapunn tentangg hubungan inii, dann mungkinn inii jugaa saatnyaa yaa sayangg, kitaa haruss ceritaa keluhh kesahh selamaa kitaa berpacaran, karenaa selamaa kitaa pacarann, kamuu tuu jarangg bilangg cemburu, jarangg bilangg gasukaa inii/ituu, jarangg marah marahh dengann hall gajelass, jarangg nuntutt yangg anehh\", bahkann mintaa menceritakan keluhh kesahh punn kamuu gatauu mauu ceritaa gimanaa😭😭 that's what i really f*cking lovee uu :))))`;

    let i = 0;
    const speed = 40;
    function typeWriter() {
      if (i < text.length) {
        document.getElementById("typing").innerHTML += text.charAt(i);
        i++;
        setTimeout(typeWriter, speed);
      }
    }
    typeWriter();
  </script>
</body>
</html>
