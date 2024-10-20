MrM: MoK replace MLP
RrB: RevIN replace BatchNorm In ResUnit
RrMR: MoK+RevIN(RMoK) replace MLP
RrMRR: MoK+RevIN replace MLP & RevIN replace BatchNorm In ResUnit

RrC: RMoK replace ConvNet
RrU: RMoK replace ResUnit
RrUC: RMoK replace ConvNet & ResUnit

RrMRRUC: RMoK replace ConvNet & MLP & RevIN replace BatchNorm In ResUnit




res shape: torch.Size([32, 2, 32, 32])
xc shape: torch.Size([32, 6, 32, 32])
xp shape: torch.Size([32, 2, 32, 32])
xt shape: torch.Size([32, 2, 32, 32])
ext shape: torch.Size([32, 28])
c_out shape: torch.Size([32, 2, 32, 32])
p_out shape: torch.Size([32, 2, 32, 32])
t_out shape: torch.Size([32, 2, 32, 32])
ext_out shape: torch.Size([32, 2, 32, 32])