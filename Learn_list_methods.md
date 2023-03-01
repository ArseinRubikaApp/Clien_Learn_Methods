[
  {
    "Tasle": "getGroupInfo",
    "Tdovom": "getGroupInfo\n\nاین متود اطلاعات گپ بدست میاره \n\nتنها مقداری که میگیره گوید گپ هستش\n\nمثال:\n\napp.getGroupInfo('g0CgKBr0fd6c0216e264e904d5021b88')",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getChatsUpdate",
    "Tdovom": "getChatsUpdate\n\nپیام های جدید کل اکانتت رو نشون میده و هیچ مقداری نمیخواد\n\nمثال:\ntest = app.getChatsUpdate\n\nprint(test)",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "DeleteUserChat",
    "Tdovom": "deleteUserChat\n\nاین متود برای حذف پیوی یک کاربر مورد استفاده قرار میگیره\n\nاولین مقدار باید گوید کاربر بدی\n\nدومین مقدار last_message پیوی طرف بگیرید\n\nمثال:\n\napp.deleteUserChat(\"u0CgKBr0fd6c0216e264e904d5021b88\",\"445433\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "changeGroupLink",
    "Tdovom": "changeGroupLink\n\nاین متود لینک گروه رو تغیر میده اما به شرطی که شما آدمین گروه باشید\n\nتنها مقداری که میگیره گوید گروه است\n\nمثال:\n\napp.changeGroupLink(\"g0CgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "changeChannelLink",
    "Tdovom": "changeChannelLink\n\nاین متود لینک کانال تغیر میده اما به شرطی که شما آدمین کانال باشید\n\nتنها مقداری که میگیره گوید کانال است\n\nمثال:\n\napp.changeChannelLink(\"c0CgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "setGroupTimer",
    "Tdovom": "setGroupTimer\n\nاین متود گروه رو در حالت آرام قرار میده تنها مقدار هایی که میگیرند\n\nاول گوید گروه\n\nدوم زمان تایمر\n\n\n مثال:\n\napp.setGroupTimer(\"girjurjeheyye\",10)",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "deleteGroup",
    "Tdovom": "deleteGroup\n\nاین متود گروه رو حذف میکنه\n\nتنها مقداری که میگیره گوید گروه است\n\nمثال:\n\napp.deleteGroup(\"g0CgKBr0fd6c0216e264e904d5021b78\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getStickerSets",
    "Tdovom": "getStickerSets\n\nاین متود اطلاعات استیکر های مربوط به ایموجی رو بهتون میده\n\n\nمثال:\n\napp.getStickerSets(\"😁\")\n\nتنها مقداری که میگیره ایموجی است",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getInfoByUsername",
    "Tdovom": "getInfoByUsername\n\nاین متود اطلاعات اکانت طرف بهتون میده\n\nفقط آیدی طرف رو بدون @ وارد کنید\n\nمثال:\n\ntest = app.getInfoByUsername(\"ArseinTeam\")\n\nprint(test)",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "banGroupMember",
    "Tdovom": "banGroupMember\n\nاین متود کاربر مورد نظر رو از گروه حذف میکنه\n\nتنها مقداری که میگیره گوید گپ و گوید اکانت طرفه\n\nمثال:\n\napp.banGroupMember(\" g0CgKBr0fd6c0216e264e904d5021b88\", [\"u0CvB3x0d02d4dbde7df7096f59a5a2d\"])",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "passwordChange",
    "Tdovom": "passwordChange\n\nاین رمز 2 مرحله ای رو تغیر میده\n\nتنها مقداری که میگیره رمز فعلی اکانته\n\nمثال:\n\napp.passwordChange(\"1234\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "deletetwolocks",
    "Tdovom": "deletetwolocks\n\nاین رمز 2 مرحله ای رو حذف میکنه و رمز برمیداره\n\nتنها مقداری که میگیره رمز فعلی اکانته\n\nمثال:\n\napp.deletetwolocks(\"1234\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "twolocks",
    "Tdovom": "twolocks\n\nاین رمز 2 مرحله ای ای رو ایجاد میکنه\n\nتنها مقداری که میگیره  \n\nاول رمزی که میخوایی بزاری\n\nدوم راهنما واسه رمز\n\nمثال:\n\napp.twolocks(\"1379\",\"سال تولدم\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getChatGroup",
    "Tdovom": "getChatGroup\n\nاین پیام های گروه رو میگیره\n\nتنها مقداری که میگیره گوید گروهه\n\nمثال:\n\napp.getChatGroup(\"g0CgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  },
  {
    "Tasle": "getChatChannel",
    "Tdovom": "getChatChannel\n\nاین پیام های کانال رو میگیره\n\nتنها مقداری که میگیره گوید چنله\n\nمثال:\n\napp.getChatChannel(\"c0kgKBr0fd6c0216e264e904d5021b88\")",
    "Photo_image": false,
    "Code": false
  }
]
