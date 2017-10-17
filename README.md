# -QRCode

原控件名 ： SGQRCode。


个人备注留用



            SGQRCodeScanningVC *vc = [[SGQRCodeScanningVC alloc] init];
            [self.navigationController pushViewController:vc animated:YES];
            
            vc.rcodeExample = ^(NSString *rcodeString){
            
            };
