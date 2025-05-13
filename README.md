# ERC-20 Token Project

Dự án tạo và triển khai token ERC-20 trên mạng testnet Sepolia.

## Cài đặt

1. Clone repository:
```bash
git clone <repository-url>
cd token-erc-20
```

2. Cài đặt dependencies:
```bash
npm install
```

3. Tạo file `.env` và cập nhật các biến môi trường:
```
SEPOLIA_RPC_URL="your_sepolia_rpc_url"
PRIVATE_KEY="your_wallet_private_key"
ETHERSCAN_API_KEY="your_etherscan_api_key"
```

## Sử dụng

1. Biên dịch smart contract:
```bash
npm run compile
```

2. Deploy lên mạng Sepolia:
```bash
npm run deploy:sepolia
```

## Tính năng của Token

- Tên: Kpay
- Ký hiệu: KPAY
- Số lượng ban đầu: 1,000,000 tokens
- Có thể mint thêm token (chỉ owner)
- Có thể burn token
- Tuân thủ chuẩn ERC-20

## Kiểm tra

1. Sau khi deploy, copy địa chỉ contract được in ra console
2. Truy cập [Sepolia Etherscan](https://sepolia.etherscan.io/)
3. Dán địa chỉ contract để xem thông tin token
(0xa53bc774ED9Ddcc2996c63603E56c8EC11FE665B)
4. Thêm token vào MetaMask để kiểm tra giao dịch 