[
  {
    "Tasle": "getGroupInfo",
    "Tdovom": "getGroupInfo\n\nاین متود اطلاعات گپ بدست میاره \n\nتنها مقداری که میگیره گوید گپ هستش\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.getGroupInfo('g0CgKBr0fd6c0216e264e904d5021b88')",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getChatsUpdate",
    "Tdovom": "getChatsUpdate\n\nپیام های جدید کل اکانتت رو نشون میده و هیچ مقداری نمیخواد\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n \ntest = app.getChatsUpdate\n\nprint(test)",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "DeleteUserChat",
    "Tdovom": "deleteUserChat\n\nاین متود برای حذف پیوی یک کاربر مورد استفاده قرار میگیره\n\nاولین مقدار باید گوید کاربر بدی\n\nدومین مقدار last_message پیوی طرف بگیرید\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.deleteUserChat(\"u0CgKBr0fd6c0216e264e904d5021b88\",\"445433\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "changeGroupLink",
    "Tdovom": "changeGroupLink\n\nاین متود لینک گروه رو تغیر میده اما به شرطی که شما آدمین گروه باشید\n\nتنها مقداری که میگیره گوید گروه است\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.changeGroupLink(\"g0CgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "changeChannelLink",
    "Tdovom": "changeChannelLink\n\nاین متود لینک کانال تغیر میده اما به شرطی که شما آدمین کانال باشید\n\nتنها مقداری که میگیره گوید کانال است\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.changeChannelLink(\"c0CgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "setGroupTimer",
    "Tdovom": "setGroupTimer\n\nاین متود گروه رو در حالت آرام قرار میده تنها مقدار هایی که میگیرند\n\nاول گوید گروه\n\nدوم زمان تایمر\n\n\n مثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.setGroupTimer(\"girjurjeheyye\",10)",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "deleteGroup",
    "Tdovom": "deleteGroup\n\nاین متود گروه رو حذف میکنه\n\nتنها مقداری که میگیره گوید گروه است\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.deleteGroup(\"g0CgKBr0fd6c0216e264e904d5021b78\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getStickerSets",
    "Tdovom": "getStickerSets\n\nاین متود اطلاعات استیکر های مربوط به ایموجی رو بهتون میده\n\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.getStickerSets(\"😁\")\n\nتنها مقداری که میگیره ایموجی است",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getInfoByUsername",
    "Tdovom": "getInfoByUsername\n\nاین متود اطلاعات اکانت طرف بهتون میده\n\nفقط آیدی طرف رو بدون @ وارد کنید\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\ntest = app.getInfoByUsername(\"ArseinTeam\")\n\nprint(test)",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "banGroupMember",
    "Tdovom": "banGroupMember\n\nاین متود کاربر مورد نظر رو از گروه حذف میکنه\n\nتنها مقداری که میگیره گوید گپ و گوید اکانت طرفه\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.banGroupMember(\" g0CgKBr0fd6c0216e264e904d5021b88\", [\"u0CvB3x0d02d4dbde7df7096f59a5a2d\"])",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "passwordChange",
    "Tdovom": "passwordChange\n\nاین رمز 2 مرحله ای رو تغیر میده\n\nتنها مقداری که میگیره رمز فعلی اکانته\n\nمثال:\n\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.passwordChange(\"1234\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "deletetwolocks",
    "Tdovom": "deletetwolocks\n\nاین رمز 2 مرحله ای رو حذف میکنه و رمز برمیداره\n\nتنها مقداری که میگیره رمز فعلی اکانته\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.deletetwolocks(\"1234\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "twolocks",
    "Tdovom": "twolocks\n\nاین رمز 2 مرحله ای ای رو ایجاد میکنه\n\nتنها مقداری که میگیره  \n\nاول رمزی که میخوایی بزاری\n\nدوم راهنما واسه رمز\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.twolocks(\"1379\",\"سال تولدم\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getChatGroup",
    "Tdovom": "getChatGroup\n\nاین پیام های گروه رو میگیره\n\nتنها مقداری که میگیره گوید گروهه\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.getChatGroup(\"g0CgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getChatChannel",
    "Tdovom": "getChatChannel\n\nاین پیام های کانال رو میگیره\n\nتنها مقداری که میگیره گوید چنله\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.getChatChannel(\"c0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getChatUser",
    "Tdovom": "getChatUser\n\nاین پیام های پیوی شخص مورد نظر رو میگیره\n\nتنها مقداری که میگیره گوید پیوی طرفه\n\nمثال:\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.getChatUser(\"u0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "removeALLAvatars",
    "Tdovom": "removeALLAvatars\n\nاین تمام عکس هایی که تو پروفایل گروه یا چنل یا اکانت خود گذاشتین رو یکجا حذف میکنه\n\nتنها مقداری که میگیره گوید هستش فقط کافیه گوید چنل یا گروه یا اکانت خود را بدید\n\nمثال:\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.removeALLAvatars(\"u0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "removeAvatars",
    "Tdovom": "removeAvatars\n\nاین یکی از عکسارو  که تو پروفایل گروه یا چنل یا اکانت خود گذاشتین رو حذف میکنه \n\nتوجه: فقط یک عکس پاک میکنه\n\nتنها مقداری که میگیره گوید هستش فقط کافیه گوید چنل یا گروه یا اکانت خود را بدید\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.removeAvatars(\"u0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "block",
    "Tdovom": "block\n\nاین کاربر مورد نظر رو بلاک میکنه \n\nتنها مقداری که میگیره گوید کاربر مورد نظره\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.block(\"u0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "unblock",
    "Tdovom": "unblock\n\nاین کاربر مورد نظر رو از بلاک درمیاره\n\nتنها مقداری که میگیره گوید کاربر مورد نظره\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.unblock(\"u0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getAvatars",
    "Tdovom": "getAvatars\n\nاین اطلاعات تمام پروفایل های گروه یا چنل یا پیوی طرف رو میگیره\n\nتنها مقداری که میگیره گوید کاربر یا گروه یا چنله\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.getAvatars(\"u0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "search_inaccount",
    "Tdovom": "search_inaccount\n\nاین متن مورد نظر رو از داخل محتواهای اکانتتون سرچ میکنه\n\nتنها مقداری که میگیره متنی که میخواهید سرچ کنه\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.search_inaccount(\"روبیکا\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "search_inrubika",
    "Tdovom": "search_inrubika\n\nاین متن مورد نظر رو از داخل محتواهای کل روبیکا سرچ میکنه\n\nتنها مقداری که میگیره متنی که میخواهید سرچ کنه\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.search_inrubika(\"روبیکا\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "seeChannelbyLink",
    "Tdovom": "seeChannelbyLink\n\nاین  اطلاعات ابتدایی رو قبل از عضو شدن به وسیله لینک کانال درمیاره\n\nتنها مقداری که میگیره لینک کانال مورد نظره\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.seeChannelbyLink(\"https://rubika.ir/joinc/DHADFCCG0WXSEVSZTFPXJFNBETBSTLUM\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "seeGroupbyLink",
    "Tdovom": "seeGroupbyLink\n\nاین  اطلاعات ابتدایی رو قبل از عضو شدن به وسیله لینک گروه درمیاره\n\nتنها مقداری که میگیره لینک گروه مورد نظره\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.seeGroupbyLink(\"https://rubika.ir/joing/DHADFCCG0WXSEVSZTFPXJFNBETBSTLUM\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "joinChannelByID",
    "Tdovom": "joinChannelByID\n\nاین  با آیدی عضو کانال میشه\n\nتنها مقداری که میگیره آیدی کانال نظره\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.joinChannelByID(\"@ArseinRubika\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "joinChannelByLink",
    "Tdovom": "joinChannelByLink\n\nاین  با لینک خصوصی عضو کانال میشه\n\nتنها مقداری که میگیره آیدی لینک کانال نظره\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.joinChannelByLink(\"@ArseinRubika\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "commonGroup",
    "Tdovom": "commonGroup\n\nاین  گروه های مشترک با اون کاربر رو نشون میده\n\nتنها مقداری که میگیره گوید کاربر مورد نظره نظره\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\napp.commonGroup(\"u0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "setTypeChannel",
    "Tdovom": "setTypeChannel\n\nاین  نوع کانال رو تغیز میده مثلا عمومی یا خصوصی\n\nتنها مقداری که میگیره گوید کانال مورد نظر و نوع چنله\n\nمثال:\n\nfrom arsein import Messenger\r\n\r\napp = Messenger(\"اوث شما\")\n\nبرای خصوصی کردن چنل👇\napp.setTypeChannel(\"u0kgKBr0fd6c0216e264e904d5021b88\"،\"Private\")\nبرای عمومی کردن چنل👇\n\napp.setTypeChannel(\"u0kgKBr0fd6c0216e264e904d5021b88\"،\"Public\"",
    "Photo_image": false,
    "Code": false
  }
]
