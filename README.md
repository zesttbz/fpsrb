## FPS rainbows

- Deb gắn vào game fps
- Hiển thị FPS - Giờ - Ngày tháng - %Pin - Custom tên tuỳ ý
- Thanh FPS đổi màu rainbows

## Usage

- Thêm file `FPSDisplay.h` `FPSDisplay.m` vào project
- Khai báo `FPSDisplay.m` vào makefile

## Edit
- Editing these in `FPSDisplay.m`

- Custom tên tuỳ ý `Obj-C`
```obj-c
NSString *WMText = [NSString stringWithFormat:@" %d FPS | %@ | Pin: %0.0f  zest",(int)round(fps),mustr,batLeft]; 
```
- Rainbows Color `Obj-C`
```obj-c
self.displayLabel.textColor = [UIColor colorWithRed:arc4random()%256/255.0 green:arc4random()%256/255.0 blue:arc4random()%256/255.0 alpha:1];
```

## Author
-  [zest](https://github.com/zesttbz)
