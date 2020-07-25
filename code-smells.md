#### $1
- 依恋情结
- item.getPrice() * item.getAmount() * item.getDiscount()

#### $2
- 重复的 switch
- switch (type) {}

#### $3
- 依恋情结
- switch (each.getMovie().getPriceCode()) {}
- .append(each.getMovie().getTitle())

#### $4（？）
- 霰弹式修改
- msgSender.sendChangeNotification(from);
- new MsgSender().sendChangeNotification(account);

#### $5
- 循环语句
- for (int i = 0; i < input.length; i++) {}

#### $6
- 被拒绝的遗赠
- public abstract void provide();

#### $7
- 过长参数列表
- User(String name, Date birthday, String location, String username, String phoneNumber, String hobbies)

#### $8（？）
- 基本类型偏执
- Application.config = adminSetting.substring(4, 8) + Calendar.getInstance().get(Calendar.YEAR);

#### $9
- 数据泥团
- hasRoom(Date date, int days, int roomType)
- bookRoom(String customerName, String email, Date from, int bookingDays, int roomType)
- findRoomOptional(Date date, int days, int roomType)

#### $10
- 过长函数
- Long Method Demo

#### $11
- 夸夸其谈的通用性
- public interface HumanAble

#### $12
- 纯数据类
- LineItem

#### $13
- 注释
- User[] friendsList; // 朋友列表

#### $14
- 临时变量
- private List<ProductBatch> productBatchesToExpired;

#### $15
- 可变数据
- private Map<Item, Integer> items = new HashMap<>();

#### $16
- 数据泥团
- public Order(Sku sku, String buyerName, String buyerPhoneNumber, String buyerAddress)
- public Deliver(int deliverNumber, String size, Double weight, String buyerName, String buyerPhoneNumber, String buyerAddress)

#### $17
- 中间人
- public Person getManager() { return department.getManager(); }

#### $18
- 重复代码

#### $19
- 坏味道太多了... 过长函数

#### $20
- 基本类型偏执
- getCity(String address) { return address.substring(address.indexOf("省") + 1, address.indexOf("市")); }

#### $21
- 过长的消息链
- hasPatient 方法

#### $22
- 内幕交易
- License 和 Motorist 方法中互相频繁调用另一个类的方法

#### $23
- 异曲同工的类
- IPChecker 和 IPValidator

#### $24
- 发散式变化
- toXml 和 toText 方法