# n8n AI Avtomatlashtirish Workflow O‘rnatish Qo‘llanmasi

## Oldindan talablar
- n8n o‘rnatilgan bo‘lishi kerak (lokal yoki bulutda)
- OpenAI yoki Anthropic API kaliti
- Google Sheets API ma’lumotlari (agar Google Sheets ishlatilsa)
- Telegram bot tokeni va chat ID’si (agar Telegram ishlatilsa)

## O‘rnatish
1. n8n’ni lokal kompyuteringizga o‘rnating yoki n8n cloud’da ro‘yxatdan o‘ting.  
2. `workflows/sample_workflow.json` faylidan workflow’ni import qiling.  
3. Nodlarni sozlang, o‘z API kalitlaringiz va hisob ma’lumotlaringizni kiriting.  

## Sozlash
- **OpenAI/Anthropic Node**: Sozlamalarda API kalitini kiriting.  
- **Google Sheets Node**: Jadval ID’sini kiriting va avtorizatsiyadan o‘ting.  
- **Telegram Node**: Bot tokeni va chat ID’sini kiriting.  

## Sinovdan o‘tkazish
Webhook orqali sinov o‘tkazish uchun `examples/sample_input.json` faylidagi namunaviy kirish ma’lumotlaridan foydalaning.  

## Foydalanish
Webhook URL manziliga JSON formatdagi vazifa tavsifini o‘z ichiga olgan POST so‘rov yuboring.
