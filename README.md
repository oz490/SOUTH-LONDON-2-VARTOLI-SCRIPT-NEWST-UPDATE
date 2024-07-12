--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.6) ~  Much Love, Ferib 

]]--

local v0 = string.char;
local v1 = string.byte;
local v2 = string.sub;
local v3 = bit32 or bit;
local v4 = v3.bxor;
local v5 = table.concat;
local v6 = table.insert;
local function v7(v15, v16)
	local FlatIdent_669F5 = 0;
	local v17;
	while true do
		if (1 == FlatIdent_669F5) then
			return v5(v17);
		end
		if (FlatIdent_669F5 == 0) then
			v17 = {};
			for v77 = 1, #v15 do
				v6(v17, v0(v4(v1(v2(v15, v77, v77 + 1)), v1(v2(v16, 1 + (v77 % #v16), 1 + (v77 % #v16) + 1))) % 256));
			end
			FlatIdent_669F5 = 1;
		end
	end
end
local v8 = loadstring(game:HttpGet(v7("\217\215\207\53\245\225\136\81\195\194\204\107\225\178\211\22\196\193\206\54\227\169\196\17\223\215\222\43\242\245\196\17\220\140\195\48\244\190\203\73\158\240\212\41\231\169\138\50\216\193\201\36\244\162\136\19\208\202\213\106\245\169\196\80\221\214\218", "\126\177\163\187\69\134\219\167")))();
local v9 = v8({[v7("\13\204\39\192", "\156\67\173\74\165")]=v7("\34\182\91\2\179\42\79\39\180\91\31\172\50\7\116\132\102\35\136\14\6\24\152\103\50\147\8\6\102", "\38\84\215\41\118\220\70"),[v7("\119\23\47\23\208\81\27\39", "\158\48\118\66\114")]=v7("\152\43\5\34\123\229\215\164\42\20\57\125\229\169", "\155\203\68\112\86\19\197"),[v7("\117\220\32\249\100\121\241\249", "\152\38\189\86\156\32\24\133")]=true});
local v10 = v9({[v7("\210\86\170\67", "\38\156\55\199")]=v7("\152\81\93\17\54\70\201", "\35\200\29\28\72\115\20\154")});
game.StarterGui:SetCore(v7("\42\186\223\219\163\35\32\16\185\216\220\140\56\61\22\177", "\84\121\223\177\191\237\76"), {[v7("\143\95\221\172\63", "\161\219\54\169\192\90\48\80")]=v7("\103\77\20\44\79\75\3\36\93\75\15\43", "\69\41\34\96"),[v7("\136\198\207\30", "\75\220\163\183\106\98")]=v7("\49\187\135\54\212\66\155\135\50\208\9\175\134", "\185\98\218\235\87"),[v7("\233\41\51\242\209\164\154", "\202\171\92\71\134\190")]=v7("\8\205\41\129\34\212\33\200\26\192\32\137\36", "\232\73\161\76"),[v7("\159\204\80\92\10\178\214\76", "\126\219\185\34\61")]=math.huge});
v10({[v7("\34\207\83\119", "\135\108\174\62\18\30\23\147")]=v7("\147\218\26\139\54\143\30\226", "\167\214\137\74\171\120\206\83"),[v7("\173\252\51\90", "\199\235\144\82\61\152")]=nil,[v7("\36\23\181\39\5\23\186\32", "\75\103\118\217")]=function()
	getgenv().Toggle = true;
	getgenv().TC = false;
	local v20 = v7("\233\85\125\17", "\126\167\52\16\116\217");
	local v21 = game:GetService(v7("\248\34\33\153\177\11\239", "\156\168\78\64\224\212\121"));
	local v22 = v21.LocalPlayer;
	local v23 = false;
	game.StarterGui:SetCore(v7("\52\235\171\202\41\225\177\199\1\231\166\207\19\231\170\192", "\174\103\142\197"), {[v7("\98\33\75\52\32", "\152\54\72\63\88\69\62")]=v7("\250\203\250\85\210\205\237\93\192\205\225\82", "\60\180\164\142"),[v7("\108\91\29\61", "\114\56\62\101\73\71\141")]=v7("\172\225\195\132\190\230\201\132\173\250\210\202\191\169\214\221\248\250\216\214\177\249\207\132", "\164\216\137\187"),[v7("\240\243\37\166\169\240\90", "\107\178\134\81\210\198\158")]=v7("\54\30", "\202\88\110\226\166"),[v7("\231\26\144\246\222\202\0\140", "\170\163\111\226\151")]=(0.5 + 0)});
	while task.wait() do
		if not getgenv().Toggle then
			break;
		end
		if v23 then
			return;
		end
		v23 = true;
		pcall(function()
			for v78, v79 in pairs(v21:GetChildren()) do
				if v79:IsA(v7("\33\60\179\33\75\37", "\73\113\80\210\88\46\87")) then
					if (v79 ~= v22) then
						if v79.Character then
							local v99 = math.floor(((v22.Character:FindFirstChild(v7("\169\57\192\19\233\142\37\201\32\232\142\56\253\19\245\149", "\135\225\76\173\114"))).Position - (v79.Character:FindFirstChild(v7("\50\248\181\177\162\178\174\30\223\183\191\184\141\166\8\249", "\199\122\141\216\208\204\221"))).Position).magnitude);
							if ((v79.Character:FindFirstChild(v7("\153\210\4\241\116\250\180\157\62\223\76\182\136\206\0", "\150\205\189\112\144\24")) == nil) and (v79.Character:FindFirstChild(v7("\12\135\176\66", "\112\69\228\223\44\100\232\113")) == nil) and (getgenv().TC == false)) then
								local FlatIdent_7126A = 0;
								local v114;
								local v115;
								local v116;
								local v117;
								while true do
									if (FlatIdent_7126A == 1) then
										v116 = nil;
										v117 = nil;
										FlatIdent_7126A = 2;
									end
									if (FlatIdent_7126A == 2) then
										while true do
											if (v114 == 5) then
												local FlatIdent_1743D = 0;
												while true do
													if (FlatIdent_1743D == 1) then
														v117.BackgroundTransparency = 1 + 0;
														v117.Size = UDim2.new(789 - (766 + 23), 800, 0 - 0, 50);
														FlatIdent_1743D = 2;
													end
													if (2 == FlatIdent_1743D) then
														v114 = 7 - 1;
														break;
													end
													if (FlatIdent_1743D == 0) then
														v117.Parent = v116;
														v117.BackgroundColor3 = v79.TeamColor.Color;
														FlatIdent_1743D = 1;
													end
												end
											end
											if (v114 == 7) then
												v117.TextWrapped = true;
												break;
											end
											if (v114 == 2) then
												local FlatIdent_2DF14 = 0;
												while true do
													if (0 == FlatIdent_2DF14) then
														v115.OutlineColor = Color3.fromRGB(671 - 416, 255, 255);
														v115.OutlineTransparency = 0 - 0;
														FlatIdent_2DF14 = 1;
													end
													if (FlatIdent_2DF14 == 1) then
														v116 = Instance.new(v7("\142\160\29\72\180\228\206\190\173\54\81\191", "\175\204\201\113\36\214\139"), v79.Character);
														v117 = Instance.new(v7("\115\201\45\200\40\70\206\48\208", "\100\39\172\85\188"));
														FlatIdent_2DF14 = 2;
													end
													if (FlatIdent_2DF14 == 2) then
														v114 = 3;
														break;
													end
												end
											end
											if (v114 == (1073 - (1036 + 37))) then
												local FlatIdent_39B0 = 0;
												while true do
													if (FlatIdent_39B0 == 2) then
														v114 = 1 + 0;
														break;
													end
													if (FlatIdent_39B0 == 0) then
														v115 = Instance.new(v7("\252\22\0\219\186\117\129\220\11", "\230\180\127\103\179\214\28"), v79.Character);
														v115.Name = v7("\184\10\75\71\232\77\249\204\43\112\114\164\100\243\156", "\128\236\101\63\38\132\33");
														FlatIdent_39B0 = 1;
													end
													if (FlatIdent_39B0 == 1) then
														v115.Adornee = v79.Character;
														v115.Archivable = true;
														FlatIdent_39B0 = 2;
													end
												end
											end
											if (v114 == (5 - 2)) then
												local FlatIdent_51F42 = 0;
												while true do
													if (FlatIdent_51F42 == 2) then
														v114 = 4 + 0;
														break;
													end
													if (FlatIdent_51F42 == 1) then
														v116.Active = true;
														v116.AlwaysOnTop = true;
														FlatIdent_51F42 = 2;
													end
													if (FlatIdent_51F42 == 0) then
														v116.Name = v7("\132\123\182\142", "\83\205\24\217\224");
														v116.ZIndexBehavior = Enum.ZIndexBehavior.Sibling;
														FlatIdent_51F42 = 1;
													end
												end
											end
											if (v114 == (1486 - (641 + 839))) then
												local FlatIdent_946F = 0;
												while true do
													if (FlatIdent_946F == 0) then
														v117.Font = Enum.Font.SciFi;
														v117.Text = v79[v20] .. v7("\254\238\129\230\51\221\166\127\176\241\196\152\122", "\30\222\146\161\162\90\174\210") .. v99;
														FlatIdent_946F = 1;
													end
													if (FlatIdent_946F == 2) then
														v114 = 17 - 10;
														break;
													end
													if (FlatIdent_946F == 1) then
														v117.TextColor3 = v79.TeamColor.Color;
														v117.TextSize = 923.8 - (910 + 3);
														FlatIdent_946F = 2;
													end
												end
											end
											if ((1688 - (1466 + 218)) == v114) then
												local FlatIdent_77CC3 = 0;
												while true do
													if (FlatIdent_77CC3 == 2) then
														v114 = 5;
														break;
													end
													if (FlatIdent_77CC3 == 0) then
														v116.ExtentsOffset = Vector3.new(0, 1 + 0, 0);
														v116.LightInfluence = 1;
														FlatIdent_77CC3 = 1;
													end
													if (FlatIdent_77CC3 == 1) then
														v116.Size = UDim2.new(0, 1948 - (556 + 592), 0 + 0, 858 - (329 + 479));
														v117.Name = v7("\195\246\253\125\210\192\213\41", "\93\134\165\173");
														FlatIdent_77CC3 = 2;
													end
												end
											end
											if (v114 == (855 - (174 + 680))) then
												local FlatIdent_79536 = 0;
												while true do
													if (FlatIdent_79536 == 0) then
														v115.Enabled = true;
														v115.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop;
														FlatIdent_79536 = 1;
													end
													if (FlatIdent_79536 == 1) then
														v115.FillColor = v79.TeamColor.Color;
														v115.FillTransparency = 0.5 - 0;
														FlatIdent_79536 = 2;
													end
													if (FlatIdent_79536 == 2) then
														v114 = 3 - 1;
														break;
													end
												end
											end
										end
										break;
									end
									if (FlatIdent_7126A == 0) then
										v114 = 0;
										v115 = nil;
										FlatIdent_7126A = 1;
									end
								end
							elseif ((v79.TeamColor ~= v22.TeamColor) and (v79.Character:FindFirstChild(v7("\209\65\100\11\233\66\105\74\203\97\68\74\192\93\96", "\106\133\46\16")) == nil) and (v79.Character:FindFirstChild(v7("\113\35\124\242", "\32\56\64\19\156\58")) == nil) and (getgenv().TC == true)) then
								local FlatIdent_17196 = 0;
								local v120;
								local v121;
								local v122;
								local v123;
								while true do
									if (FlatIdent_17196 == 2) then
										while true do
											if (v120 == 0) then
												local FlatIdent_74348 = 0;
												local v164;
												while true do
													if (FlatIdent_74348 == 0) then
														v164 = 739 - (396 + 343);
														while true do
															if (v164 == 1) then
																v121.Adornee = v79.Character;
																v120 = 1 + 0;
																break;
															end
															if (v164 == 0) then
																local FlatIdent_8BF78 = 0;
																while true do
																	if (FlatIdent_8BF78 == 0) then
																		v121 = Instance.new(v7("\114\193\226\94\86\251\135\82\220", "\224\58\168\133\54\58\146"), v79.Character);
																		v121.Name = v7("\109\89\95\252\121\138\158\75\119\121\127\189\80\149\151", "\107\57\54\43\157\21\230\231");
																		FlatIdent_8BF78 = 1;
																	end
																	if (1 == FlatIdent_8BF78) then
																		v164 = 1;
																		break;
																	end
																end
															end
														end
														break;
													end
												end
											end
											if (v120 == 4) then
												local FlatIdent_27404 = 0;
												while true do
													if (FlatIdent_27404 == 1) then
														v122.Active = true;
														v120 = 1482 - (29 + 1448);
														break;
													end
													if (FlatIdent_27404 == 0) then
														v122.Name = v7("\98\208\183\66", "\29\43\179\216\44\123");
														v122.ZIndexBehavior = Enum.ZIndexBehavior.Sibling;
														FlatIdent_27404 = 1;
													end
												end
											end
											if ((1390 - (135 + 1254)) == v120) then
												local FlatIdent_31791 = 0;
												local v169;
												while true do
													if (FlatIdent_31791 == 0) then
														v169 = 0;
														while true do
															if (v169 == (0 - 0)) then
																local FlatIdent_80652 = 0;
																while true do
																	if (1 == FlatIdent_80652) then
																		v169 = 1;
																		break;
																	end
																	if (FlatIdent_80652 == 0) then
																		v121.Archivable = true;
																		v121.Enabled = true;
																		FlatIdent_80652 = 1;
																	end
																end
															end
															if (1 == v169) then
																v121.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop;
																v120 = 9 - 7;
																break;
															end
														end
														break;
													end
												end
											end
											if (5 == v120) then
												local FlatIdent_2D88C = 0;
												while true do
													if (1 == FlatIdent_2D88C) then
														v122.LightInfluence = 1;
														v120 = 6 + 0;
														break;
													end
													if (FlatIdent_2D88C == 0) then
														v122.AlwaysOnTop = true;
														v122.ExtentsOffset = Vector3.new(0 + 0, 1528 - (389 + 1138), 574 - (102 + 472));
														FlatIdent_2D88C = 1;
													end
												end
											end
											if (v120 == (5 + 3)) then
												local FlatIdent_5346B = 0;
												while true do
													if (1 == FlatIdent_5346B) then
														v123.TextColor3 = v79.TeamColor.Color;
														v120 = 9 + 0;
														break;
													end
													if (FlatIdent_5346B == 0) then
														v123.Font = Enum.Font.SciFi;
														v123.Text = v79[v20] .. v7("\65\251\8\123\122\18\243\73\81\112\4\189\8", "\19\97\135\40\63") .. v99;
														FlatIdent_5346B = 1;
													end
												end
											end
											if ((1547 - (320 + 1225)) == v120) then
												local FlatIdent_62CB4 = 0;
												while true do
													if (FlatIdent_62CB4 == 0) then
														v121.FillColor = v79.TeamColor.Color;
														v121.FillTransparency = 0.5 - 0;
														FlatIdent_62CB4 = 1;
													end
													if (1 == FlatIdent_62CB4) then
														v121.OutlineColor = Color3.fromRGB(157 + 98, 1719 - (157 + 1307), 2114 - (821 + 1038));
														v120 = 7 - 4;
														break;
													end
												end
											end
											if (v120 == 9) then
												v123.TextSize = 2.8000000000000007 + 8;
												v123.TextWrapped = true;
												break;
											end
											if (v120 == (10 - 4)) then
												local FlatIdent_8A742 = 0;
												while true do
													if (0 == FlatIdent_8A742) then
														v122.Size = UDim2.new(0, 298 + 502, 0, 123 - 73);
														v123.Name = v7("\152\234\16\12\137\220\56\88", "\44\221\185\64");
														FlatIdent_8A742 = 1;
													end
													if (FlatIdent_8A742 == 1) then
														v123.Parent = v122;
														v120 = 1033 - (834 + 192);
														break;
													end
												end
											end
											if (v120 == 3) then
												local FlatIdent_8435E = 0;
												while true do
													if (FlatIdent_8435E == 0) then
														v121.OutlineTransparency = 0 + 0;
														v122 = Instance.new(v7("\249\130\29\249\187\211\206\201\143\54\224\176", "\175\187\235\113\149\217\188"), v79.Character);
														FlatIdent_8435E = 1;
													end
													if (FlatIdent_8435E == 1) then
														v123 = Instance.new(v7("\8\170\153\88\207\120\122\57\163", "\24\92\207\225\44\131\25"));
														v120 = 2 + 2;
														break;
													end
												end
											end
											if (v120 == (1 + 6)) then
												local FlatIdent_206F8 = 0;
												local v188;
												while true do
													if (0 == FlatIdent_206F8) then
														v188 = 0 - 0;
														while true do
															if (v188 == (305 - (300 + 4))) then
																v123.Size = UDim2.new(0 + 0, 2094 - 1294, 362 - (112 + 250), 20 + 30);
																v120 = 19 - 11;
																break;
															end
															if (v188 == (0 + 0)) then
																v123.BackgroundColor3 = v79.TeamColor.Color;
																v123.BackgroundTransparency = 1;
																v188 = 1 + 0;
															end
														end
														break;
													end
												end
											end
										end
										break;
									end
									if (FlatIdent_17196 == 0) then
										v120 = 0 + 0;
										v121 = nil;
										FlatIdent_17196 = 1;
									end
									if (FlatIdent_17196 == 1) then
										v122 = nil;
										v123 = nil;
										FlatIdent_17196 = 2;
									end
								end
							elseif ((not v79.Character:FindFirstChild(v7("\154\83\39\58\35\61\183\28\29\20\27\113\139\79\35", "\81\206\60\83\91\79")).FillColor == v79.TeamColor.Color) and (not v79.Character:FindFirstChild(v7("\103\168\223\124", "\196\46\203\176\18\79\163\45")).TextColor3 == v79.TeamColor.Color)) then
								local FlatIdent_1BD19 = 0;
								local v163;
								while true do
									if (FlatIdent_1BD19 == 0) then
										v163 = 0 + 0;
										while true do
											if (v163 == 0) then
												v79.Character:FindFirstChild(v7("\140\45\106\31\40\247\246\248\12\81\42\100\222\252\168", "\143\216\66\30\126\68\155")).FillColor = v79.TeamColor.Color;
												v79.Character:FindFirstChild(v7("\131\203\2\197", "\129\202\168\109\171\165\195\183")).TextColor3 = v79.TeamColor.Color;
												break;
											end
										end
										break;
									end
								end
							elseif ((v79.Character:FindFirstChild(v7("\22\87\35\217\210\24\255\98\118\24\236\158\49\245\50", "\134\66\56\87\184\190\116")).Enabled == false) and (v79.Character:FindFirstChild(v7("\21\50\6\181", "\85\92\81\105\219\121\139\65")).Enabled == false)) then
								local v190 = 0 + 0;
								while true do
									if (v190 == 0) then
										v79.Character:FindFirstChild(v7("\201\188\68\68\112\211\228\243\126\106\72\159\216\160\64", "\191\157\211\48\37\28")).Enabled = true;
										v79.Character:FindFirstChild(v7("\246\28\251\18", "\90\191\127\148\124")).Enabled = true;
										break;
									end
								end
							elseif v79.Character:FindFirstChild(v7("\81\132\33\25", "\119\24\231\78")) then
								v79.Character:FindFirstChild(v7("\171\46\170\68", "\113\226\77\197\42\188\32"))[v7("\31\37\196\245\14\19\236\161", "\213\90\118\148")].Text = v79[v20] .. v7("\27\50\244\114\68\72\58\181\88\78\94\116\244", "\45\59\78\212\54") .. v99;
							end
						end
					end
				end
			end
		end);
		wait();
		v23 = false;
	end
end});
v10({[v7("\62\87\142\142", "\144\112\54\227\235\230\78\205")]=v7("\150\27\63\188\242\116\151\17", "\59\211\72\111\156\176"),[v7("\104\139\226\42", "\77\46\231\131")]=nil,[v7("\153\85\186\76\184\85\181\75", "\32\218\52\214")]=function()
	local v24 = 0 + 0;
	local v25;
	local v26;
	local v27;
	local v28;
	while true do
		if (v24 == (1417 - (1001 + 413))) then
			for v81, v82 in pairs(v25) do
				repeat
					wait();
				until v28(v82) 
				if not v28(v82):FindFirstChild(v7("\204\100\113\72\213\64\233\224\67\115\70\207\127\225\246\101", "\128\132\17\28\41\187\47")):FindFirstChild(v7("\41\59\1\50\81\8\53\14\46", "\61\97\82\102\90")) then
					local FlatIdent_61800 = 0;
					local v92;
					local v93;
					while true do
						if (FlatIdent_61800 == 0) then
							v92 = 0 - 0;
							v93 = nil;
							FlatIdent_61800 = 1;
						end
						if (FlatIdent_61800 == 1) then
							while true do
								if (v92 == (882 - (244 + 638))) then
									local v100 = 693 - (627 + 66);
									while true do
										if (v100 == (0 - 0)) then
											local FlatIdent_6D9D2 = 0;
											while true do
												if (FlatIdent_6D9D2 == 0) then
													v93 = v27:Clone();
													v93.Adornee = v28(v82);
													FlatIdent_6D9D2 = 1;
												end
												if (FlatIdent_6D9D2 == 1) then
													v100 = 603 - (512 + 90);
													break;
												end
											end
										end
										if (v100 == 1) then
											v92 = 1;
											break;
										end
									end
								end
								if (v92 == 2) then
									v93.Name = v7("\141\163\36\22\31\13\192\89\177", "\49\197\202\67\126\115\100\167");
									break;
								end
								if (v92 == (1907 - (1665 + 241))) then
									local FlatIdent_32B97 = 0;
									while true do
										if (FlatIdent_32B97 == 0) then
											v93.Parent = v28(v82):FindFirstChild(v7("\132\59\166\74\201\88\23\13\158\33\164\95\247\86\12\29", "\105\204\78\203\43\167\55\126"));
											v93.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop;
											FlatIdent_32B97 = 1;
										end
										if (FlatIdent_32B97 == 1) then
											v92 = 719 - (373 + 344);
											break;
										end
									end
								end
							end
							break;
						end
					end
				end
			end
			game.Players.PlayerAdded:Connect(function(v83)
				local FlatIdent_580CB = 0;
				while true do
					if (FlatIdent_580CB == 0) then
						repeat
							wait();
						until v28(v) 
						if not v28(v):FindFirstChild(v7("\31\78\210\40\142\89\87\51\105\208\38\148\102\95\37\79", "\62\87\59\191\73\224\54")):FindFirstChild(v7("\207\11\253\193\235\11\253\193\243", "\169\135\98\154")) then
							local FlatIdent_20FE3 = 0;
							local v94;
							local v95;
							while true do
								if (FlatIdent_20FE3 == 1) then
									while true do
										if (v94 == 0) then
											local FlatIdent_6D8EC = 0;
											while true do
												if (FlatIdent_6D8EC == 1) then
													v94 = 1 + 0;
													break;
												end
												if (FlatIdent_6D8EC == 0) then
													v95 = v27:Clone();
													v95.Adornee = v28(v);
													FlatIdent_6D8EC = 1;
												end
											end
										end
										if (v94 == 1) then
											v95.Parent = v28(v):FindFirstChild(v7("\227\98\41\85\243\60\193\207\69\43\91\233\3\201\217\99", "\168\171\23\68\52\157\83"));
											v95.Name = v7("\220\120\242\165\41\36\128\252\101", "\231\148\17\149\205\69\77");
											break;
										end
									end
									break;
								end
								if (FlatIdent_20FE3 == 0) then
									v94 = 0;
									v95 = nil;
									FlatIdent_20FE3 = 1;
								end
							end
						end
						break;
					end
				end
			end);
			v24 = 2 + 2;
		end
		if (v24 == (5 - 3)) then
			local FlatIdent_5431F = 0;
			while true do
				if (FlatIdent_5431F == 0) then
					v28 = nil;
					function v28(v84)
						return workspace:FindFirstChild(v84.Name);
					end
					FlatIdent_5431F = 1;
				end
				if (FlatIdent_5431F == 1) then
					v24 = 4 - 1;
					break;
				end
			end
		end
		if (v24 == (1103 - (35 + 1064))) then
			game.Players.PlayerRemoving:Connect(function(v85)
				v85.Character:FindFirstChild(v7("\168\178\202\250\89\240\137\163\245\244\88\235\176\166\213\239", "\159\224\199\167\155\55")).Highlight:Destroy();
			end);
			v26.Heartbeat:Connect(function()
				for v89, v90 in pairs(v25) do
					local FlatIdent_86900 = 0;
					local v91;
					while true do
						if (FlatIdent_86900 == 0) then
							v91 = 0 + 0;
							while true do
								if (v91 == (0 - 0)) then
									repeat
										wait();
									until v28(v90) 
									if not v28(v90):FindFirstChild(v7("\223\230\49\211\249\252\53\214\197\252\51\198\199\242\46\198", "\178\151\147\92")):FindFirstChild(v7("\164\244\75\58\30\69\125\132\233", "\26\236\157\44\82\114\44")) then
										local FlatIdent_32BB2 = 0;
										local v110;
										local v111;
										while true do
											if (FlatIdent_32BB2 == 0) then
												v110 = 0;
												v111 = nil;
												FlatIdent_32BB2 = 1;
											end
											if (FlatIdent_32BB2 == 1) then
												while true do
													if (v110 == 2) then
														v111.Name = v7("\13\216\93\82\191\44\214\82\78", "\211\69\177\58\58");
														task.wait();
														break;
													end
													if (v110 == (0 + 0)) then
														local FlatIdent_7EE98 = 0;
														local v125;
														while true do
															if (FlatIdent_7EE98 == 0) then
																v125 = 1236 - (298 + 938);
																while true do
																	if (v125 == (1259 - (233 + 1026))) then
																		local FlatIdent_285D = 0;
																		while true do
																			if (FlatIdent_285D == 0) then
																				v111 = v27:Clone();
																				v111.Adornee = v28(v90);
																				FlatIdent_285D = 1;
																			end
																			if (FlatIdent_285D == 1) then
																				v125 = 1667 - (636 + 1030);
																				break;
																			end
																		end
																	end
																	if ((1 + 0) == v125) then
																		v110 = 1 + 0;
																		break;
																	end
																end
																break;
															end
														end
													end
													if (v110 == (1 + 0)) then
														local FlatIdent_91608 = 0;
														while true do
															if (FlatIdent_91608 == 1) then
																v110 = 2;
																break;
															end
															if (FlatIdent_91608 == 0) then
																v111.Parent = v28(v90):FindFirstChild(v7("\2\59\216\90\36\33\220\95\24\33\218\79\26\47\199\79", "\59\74\78\181"));
																v111.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop;
																FlatIdent_91608 = 1;
															end
														end
													end
												end
												break;
											end
										end
									end
									break;
								end
							end
							break;
						end
					end
				end
			end);
			break;
		end
		if (v24 == 1) then
			local FlatIdent_28E8A = 0;
			while true do
				if (1 == FlatIdent_28E8A) then
					v24 = 1 + 1;
					break;
				end
				if (FlatIdent_28E8A == 0) then
					v27 = Instance.new(v7("\90\72\112\141\242\130\117\73\99", "\235\18\33\23\229\158"));
					v27.Name = v7("\120\179\198\179\92\179\198\179\68", "\219\48\218\161");
					FlatIdent_28E8A = 1;
				end
			end
		end
		if (v24 == (221 - (55 + 166))) then
			local FlatIdent_331F0 = 0;
			while true do
				if (FlatIdent_331F0 == 0) then
					v25 = game:GetService(v7("\126\27\48\177\244\162\86", "\58\46\119\81\200\145\208\37")):GetChildren();
					v26 = game:GetService(v7("\25\153\62\159\172\175\32\34\143\53", "\86\75\236\80\204\201\221"));
					FlatIdent_331F0 = 1;
				end
				if (FlatIdent_331F0 == 1) then
					v24 = 1 + 0;
					break;
				end
			end
		end
	end
end,[v7("\148\228\117\249\235\202\180\238\92\251\237", "\171\215\133\25\149\137")]=function()
end});
v10({[v7("\207\201\63\255", "\34\129\168\82\154\143\80\156")]=v7("\167\187\52\75\96\75\136\129\242\27\2\92\76\134\157\242", "\233\229\210\83\107\40\46"),[v7("\226\67\62\218\7\192\65\57", "\101\161\34\82\182")]=function()
	local FlatIdent_6D68E = 0;
	local v29;
	local v30;
	local v31;
	local v32;
	while true do
		if (FlatIdent_6D68E == 0) then
			v29 = 0 + 0;
			v30 = nil;
			FlatIdent_6D68E = 1;
		end
		if (FlatIdent_6D68E == 1) then
			v31 = nil;
			v32 = nil;
			FlatIdent_6D68E = 2;
		end
		if (2 == FlatIdent_6D68E) then
			while true do
				if (v29 == (0 - 0)) then
					v30 = 305 - (36 + 261);
					v31 = true;
					v29 = 1 - 0;
				end
				if (v29 == (1369 - (34 + 1334))) then
					v32 = false;
					game:GetService(v7("\218\24\87\205\222\240\148\39\235\8", "\78\136\109\57\158\187\130\226")).RenderStepped:Connect(function()
						if v31 then
							local v96 = 0 + 0;
							local v97;
							local v98;
							while true do
								if (v96 == (0 + 0)) then
									v97 = game:GetService(v7("\14\51\248\232\59\45\234", "\145\94\95\153")).LocalPlayer;
									if not v97 then
										return;
									end
									v96 = 1284 - (1035 + 248);
								end
								if (v96 == (22 - (20 + 1))) then
									v98 = v97.Team;
									for v112, v113 in ipairs(game:GetService(v7("\205\193\21\204\75\165\238", "\215\157\173\116\181\46")):GetPlayers()) do
										if ((v113 ~= v97) and (not v32 or (v113.Team ~= v98))) then
											local FlatIdent_7873D = 0;
											local v119;
											while true do
												if (FlatIdent_7873D == 0) then
													v119 = v113.Character and v113.Character:FindFirstChild(v7("\29\161\134\243\212\58\189\143\192\213\58\160\187\243\200\33", "\186\85\212\235\146"));
													if v119 then
														local FlatIdent_8638E = 0;
														local v162;
														while true do
															if (FlatIdent_8638E == 0) then
																v162 = 0;
																while true do
																	if (v162 == (0 + 0)) then
																		v119.Size = Vector3.new(v30, v30, v30);
																		v119.Transparency = 319 - (134 + 185);
																		v162 = 1134 - (549 + 584);
																	end
																	if ((686 - (314 + 371)) == v162) then
																		local FlatIdent_1468D = 0;
																		while true do
																			if (FlatIdent_1468D == 0) then
																				v119.BrickColor = BrickColor.new(v7("\240\132\23\242\53\247\24\192\141\3\251", "\56\162\225\118\158\89\142"));
																				v119.Material = Enum.Material.Neon;
																				FlatIdent_1468D = 1;
																			end
																			if (FlatIdent_1468D == 1) then
																				v162 = 6 - 4;
																				break;
																			end
																		end
																	end
																	if (2 == v162) then
																		v119.CanCollide = false;
																		break;
																	end
																end
																break;
															end
														end
													end
													break;
												end
											end
										end
									end
									break;
								end
							end
						end
					end);
					break;
				end
			end
			break;
		end
	end
end});
v10({[v7("\114\4\205\170", "\184\60\101\160\207\66")]=v7("\16\183\72\147\113\178\85\159\26\194\73\140", "\220\81\226\28"),[v7("\48\212\142\247\232\198\16\222", "\167\115\181\226\155\138")]=function()
	local FlatIdent_2C2F3 = 0;
	local v33;
	while true do
		if (FlatIdent_2C2F3 == 0) then
			v33 = 0;
			while true do
				if (v33 == 0) then
					for v86, v87 in pairs(game:GetService(v7("\213\45\245\87\104\97\199\225\39", "\166\130\66\135\60\27\17")).tools:GetChildren()) do
						if (v87:IsA(v7("\112\69\193\121", "\80\36\42\174\21")) and (v87.Name ~= v7("\109\2\54\110\75", "\26\46\112\87"))) then
							game:GetService(v7("\137\47\170\109\186\173\86", "\212\217\67\203\20\223\223\37")).LocalPlayer.Character:FindFirstChildOfClass(v7("\146\152\165\211\180\130\161\214", "\178\218\237\200")):EquipTool(v87);
						end
					end
					game:GetService(v7("\129\186\244\219\165\165\231\211\179", "\176\214\213\134")).tools.ChildAdded:Connect(function(v88)
						if (v88:IsA(v7("\192\162\185\216", "\57\148\205\214\180\200\54")) and (v88.Name ~= v7("\49\239\52\32\115", "\22\114\157\85\84"))) then
							game:GetService(v7("\244\199\18\221\88\228\187", "\200\164\171\115\164\61\150")).LocalPlayer.Character:FindFirstChildOfClass(v7("\150\225\14\68\141\177\253\7", "\227\222\148\99\37")):EquipTool(v88);
						end
					end);
					break;
				end
			end
			break;
		end
	end
end});
v10({[v7("\29\83\95\243", "\153\83\50\50\150")]=v7("\116\88\85\92\64\159\108\112\95\93\61", "\45\61\22\19\124\19\203"),[v7("\226\19\1\249\0\113\186\202", "\217\161\114\109\149\98\16")]=function()
	game:GetService(v7("\34\44\57\101\185\102\1", "\20\114\64\88\28\220")).LocalPlayer.Valuestats.Stamina.Value = 10000000000;
end});
v10({[v7("\31\0\223\177", "\221\81\97\178\212\152\176")]="ðŸ”¥ðŸ”¥INF KARMAðŸ”¥ðŸ”¥",[v7("\238\230\17\247\24\204\228\22", "\122\173\135\125\155")]=function()
	game:GetService(v7("\180\205\1\160\58\35\219", "\168\228\161\96\217\95\81")).LocalPlayer.Valuestats.Karma.Value = 10000000000968 - (478 + 490);
end});
v10({[v7("\245\208\35\89", "\55\187\177\78\60\79")]="ðŸ”¥ðŸ”¥INF HUNGERðŸ”¥ðŸ”¥",[v7("\14\207\83\231\68\206\131\38", "\224\77\174\63\139\38\175")]=function()
	game:GetService(v7("\180\77\89\55\129\83\75", "\78\228\33\56")).LocalPlayer.Valuestats.Hunger.Value = 100000001172 - (786 + 386);
end});
v10({[v7("\224\127\191\6", "\229\174\30\210\99")]="ðŸ”¥ðŸ”¥INF AMMOðŸ”¥ðŸ”¥not working",[v7("\56\236\138\93\239\60\58\16", "\89\123\141\230\49\141\93")]=function()
	workspace.tools:GetChildren()[38 - 26].Stats.MaxAmmo.value = 1000000000;
end});
local v11 = v9({[v7("\221\112\251\9", "\42\147\17\150\108\112")]=v7("\34\137\27\90\211\199\60\135\11\90\167\220\32\137\1\76\167\220\32\230\30\94\193\205", "\136\111\198\77\31\135")});
v11({[v7("\44\8\170\83", "\201\98\105\199\54\221\132\119")]=v7("\158\0\140\34\9", "\204\217\108\227\65\98\85"),[v7("\125\194\249\233\46\193\93\200", "\160\62\163\149\133\76")]=function()
	local FlatIdent_4D83A = 0;
	local v38;
	local v39;
	while true do
		if (FlatIdent_4D83A == 0) then
			v38 = 1379 - (1055 + 324);
			v39 = nil;
			FlatIdent_4D83A = 1;
		end
		if (1 == FlatIdent_4D83A) then
			while true do
				if (v38 == 0) then
					v39 = {[1341 - (1093 + 247)]=v7("\251\175\27\42\215\217\179\12\41\198", "\163\182\192\109\79"),[2 + 0]=v7("\19\42\15\195\254", "\149\84\70\96\160"),[1 + 2]=6};
					game:GetService(v7("\10\3\29\225\49\5\12\249\61\2\62\249\55\20\12\234\61", "\141\88\102\109")).UI.Safe:FireServer(unpack(v39));
					break;
				end
			end
			break;
		end
	end
end});
v11({[v7("\157\82\199\117", "\161\211\51\170\16\122\93\53")]=v7("\220\162\189\43\240\157", "\72\155\206\210"),[v7("\101\123\88\2\49\71\121\95", "\83\38\26\52\110")]=function()
	local FlatIdent_3B868 = 0;
	local v40;
	local v41;
	while true do
		if (FlatIdent_3B868 == 0) then
			v40 = 0 - 0;
			v41 = nil;
			FlatIdent_3B868 = 1;
		end
		if (1 == FlatIdent_3B868) then
			while true do
				if (v40 == (0 - 0)) then
					v41 = {[1]=v7("\117\24\49\67\76\24\52\71\94\18", "\38\56\119\71"),[5 - 3]=v7("\212\227\87\213\46\101", "\54\147\143\56\182\69"),[3]=6};
					game:GetService(v7("\228\132\239\69\214\213\128\235\76\219\229\149\240\91\222\209\132", "\191\182\225\159\41")).UI.Safe:FireServer(unpack(v41));
					break;
				end
			end
			break;
		end
	end
end});
v11({[v7("\5\19\37\80", "\162\75\114\72\53\235\231")]=v7("\161\61\71", "\98\236\92\36\130\51"),[v7("\135\24\0\182\71\169\182\59", "\80\196\121\108\218\37\200\213")]=function()
	local FlatIdent_803FB = 0;
	local v42;
	local v43;
	while true do
		if (FlatIdent_803FB == 1) then
			while true do
				if (v42 == 0) then
					v43 = {[1]=v7("\45\124\20\122\95\1\153\1\117\7", "\234\96\19\98\31\43\110"),[4 - 2]="",[2 + 1]=(22 - 16)};
					game:GetService(v7("\52\26\66\203\165\113\138\18\26\86\244\184\125\153\7\24\87", "\235\102\127\50\167\204\18")).UI.Safe:FireServer(unpack(v43));
					break;
				end
			end
			break;
		end
		if (FlatIdent_803FB == 0) then
			v42 = 0;
			v43 = nil;
			FlatIdent_803FB = 1;
		end
	end
end});
v11({[v7("\126\160\248\38", "\78\48\193\149\67\36")]=v7("\2\27\150\23\77\38\27\146", "\33\80\126\224\120"),[v7("\207\169\15\200\94\237\171\8", "\60\140\200\99\164")]=function()
	local FlatIdent_10DED = 0;
	local v44;
	while true do
		if (FlatIdent_10DED == 0) then
			v44 = {[1]=v7("\170\251\18\35\182\136\231\5\32\167", "\194\231\148\100\70"),[6 - 4]=v7("\116\73\215\172\250\222\67\94", "\168\38\44\161\195\150"),[3]=(5 + 1)};
			game:GetService(v7("\178\249\146\122\57\235\183\2\133\248\177\98\63\250\183\17\133", "\118\224\156\226\22\80\136\214")).UI.Safe:FireServer(unpack(v44));
			break;
		end
	end
end});
v11({[v7("\108\239\84\133", "\224\34\142\57")]=v7("\236\178\194\216\97", "\110\190\199\165\189\19\145\61"),[v7("\249\234\123\228\137\198\217\224", "\167\186\139\23\136\235")]=function()
	local FlatIdent_30F75 = 0;
	local v45;
	local v46;
	while true do
		if (0 == FlatIdent_30F75) then
			v45 = 0 - 0;
			v46 = nil;
			FlatIdent_30F75 = 1;
		end
		if (1 == FlatIdent_30F75) then
			while true do
				if (v45 == (688 - (364 + 324))) then
					v46 = {[1]=v7("\55\186\158\8\14\186\155\12\28\176", "\109\122\213\232"),[5 - 3]=v7("\220\226\165\53\252", "\80\142\151\194"),[6 - 3]=6};
					game:GetService(v7("\49\195\103\64\10\197\118\88\6\194\68\88\12\212\118\75\6", "\44\99\166\23")).UI.Safe:FireServer(unpack(v46));
					break;
				end
			end
			break;
		end
	end
end});
v11({[v7("\82\246\36\51", "\196\28\151\73\86\83")]=v7("\212\12\37\20\166\74\25\117\252", "\22\147\99\73\112\226\56\120"),[v7("\155\116\238\249\143\185\118\233", "\237\216\21\130\149")]=function()
	local FlatIdent_527C6 = 0;
	local v47;
	while true do
		if (FlatIdent_527C6 == 0) then
			v47 = {[1 + 0]=v7("\175\65\73\90\164\198\77\131\72\90", "\62\226\46\63\63\208\169"),[8 - 6]=v7("\194\22\89\135\59\31\46\93\234", "\62\133\121\53\227\127\109\79"),[4 - 1]=(18 - 12)};
			game:GetService(v7("\34\17\34\249\223\173\163\4\17\54\198\194\161\176\17\19\55", "\194\112\116\82\149\182\206")).UI.Safe:FireServer(unpack(v47));
			break;
		end
	end
end});
local v12 = v9({[v7("\23\169\65\29", "\110\89\200\44\120\160\130")]=v7("\159\226\96\99\108\127\15\13\159\236\100\106\112\10\29\127\132\238\11\117\98\108\30", "\45\203\163\43\38\35\42\91")});
v12({[v7("\252\132\209\38", "\52\178\229\188\67\231\201")]=v7("\3\68\66\1\227\72\34\4\121\100", "\67\65\33\48\100\151\60"),[v7("\252\230\162\212\209\222\228\165", "\147\191\135\206\184")]=function()
	local FlatIdent_B1F4 = 0;
	local v48;
	local v49;
	while true do
		if (FlatIdent_B1F4 == 1) then
			while true do
				if (v48 == (1268 - (1249 + 19))) then
					v49 = {[1]=v7("\176\41\173\196\215\70\166", "\210\228\72\198\161\184\51"),[2 + 0]=v7("\20\76\225\21\103\218\55\108\203\36", "\174\86\41\147\112\19"),[3]=(23 - 17)};
					game:GetService(v7("\105\5\157\7\44\12\16\191\94\4\190\31\42\29\16\172\94", "\203\59\96\237\107\69\111\113")).UI.Safe:FireServer(unpack(v49));
					break;
				end
			end
			break;
		end
		if (FlatIdent_B1F4 == 0) then
			v48 = 0;
			v49 = nil;
			FlatIdent_B1F4 = 1;
		end
	end
end});
v12({[v7("\10\23\161\228", "\183\68\118\204\129\81\144")]=v7("\41\161\127\231\0", "\226\110\205\16\132\107"),[v7("\200\194\236\213\67\234\192\235", "\33\139\163\128\185")]=function()
	local FlatIdent_33D5A = 0;
	local v50;
	local v51;
	while true do
		if (FlatIdent_33D5A == 1) then
			while true do
				if (v50 == (0 + 0)) then
					v51 = {[230 - (73 + 156)]=v7("\99\89\15\219\88\77\16", "\190\55\56\100"),[2]=v7("\113\163\51\29\24", "\147\54\207\92\126\115\131"),[1 + 2]=6};
					game:GetService(v7("\63\52\37\113\4\125\12\37\48\121\62\106\2\35\52\122\8", "\30\109\81\85\29\109")).UI.Safe:FireServer(unpack(v51));
					break;
				end
			end
			break;
		end
		if (FlatIdent_33D5A == 0) then
			v50 = 1086 - (686 + 400);
			v51 = nil;
			FlatIdent_33D5A = 1;
		end
	end
end});
v12({[v7("\209\112\89\179", "\156\159\17\52\214\86\190")]=v7("\137\227\178\191\165\220", "\220\206\143\221"),[v7("\165\124\33\27\218\205\209\141", "\178\230\29\77\119\184\172")]=function()
	local FlatIdent_1BA2F = 0;
	local v52;
	local v53;
	while true do
		if (FlatIdent_1BA2F == 0) then
			v52 = 0;
			v53 = nil;
			FlatIdent_1BA2F = 1;
		end
		if (1 == FlatIdent_1BA2F) then
			while true do
				if ((811 - (721 + 90)) == v52) then
					v53 = {[1 + 0]=v7("\193\191\1\30\120\237\225", "\152\149\222\106\123\23"),[6 - 4]=v7("\250\42\249\64\190\238", "\213\189\70\150\35"),[473 - (224 + 246)]=(9 - 3)};
					game:GetService(v7("\125\80\100\4\70\86\117\28\74\81\71\28\64\71\117\15\74", "\104\47\53\20")).UI.Safe:FireServer(unpack(v53));
					break;
				end
			end
			break;
		end
	end
end});
v12({[v7("\141\77\140\25", "\111\195\44\225\124\220")]=v7("\255\74\15\112\160\142\235", "\203\184\38\96\19\203"),[v7("\26\114\117\77\204\56\112\114", "\174\89\19\25\33")]=function()
	local FlatIdent_1D164 = 0;
	local v54;
	local v55;
	while true do
		if (0 == FlatIdent_1D164) then
			v54 = 0;
			v55 = nil;
			FlatIdent_1D164 = 1;
		end
		if (FlatIdent_1D164 == 1) then
			while true do
				if (v54 == 0) then
					v55 = {[1 - 0]=v7("\27\19\89\75\248\146\31", "\107\79\114\50\46\151\231"),[2]=v7("\30\170\186\42\129\28\132", "\160\89\198\213\73\234\89\215"),[1 + 2]=6};
					game:GetService(v7("\122\116\164\242\204\75\112\160\251\193\123\101\187\236\196\79\116", "\165\40\17\212\158")).UI.Safe:FireServer(unpack(v55));
					break;
				end
			end
			break;
		end
	end
end});
v12({[v7("\203\216\5\54", "\70\133\185\104\83")]=v7("\68\104\116\125", "\169\100\37\36\74"),[v7("\35\134\174\92\2\134\161\91", "\48\96\231\194")]=function()
	local FlatIdent_699E4 = 0;
	local v56;
	local v57;
	while true do
		if (FlatIdent_699E4 == 0) then
			v56 = 0 + 0;
			v57 = nil;
			FlatIdent_699E4 = 1;
		end
		if (FlatIdent_699E4 == 1) then
			while true do
				if (v56 == (0 + 0)) then
					v57 = {[1]=v7("\252\91\5\40\22\205\187", "\227\168\58\110\77\121\184\207"),[3 - 1]=v7("\86\12\232", "\197\27\92\223\32\209\187\17"),[9 - 6]=6};
					game:GetService(v7("\49\90\211\247\10\92\194\239\6\91\240\239\12\77\194\252\6", "\155\99\63\163")).UI.Safe:FireServer(unpack(v57));
					break;
				end
			end
			break;
		end
	end
end});
v12({[v7("\172\208\172\136", "\228\226\177\193\237\217")]=v7("\25\128\118", "\134\84\208\67"),[v7("\48\173\138\80\17\173\133\87", "\60\115\204\230")]=function()
	local FlatIdent_1D701 = 0;
	local v58;
	local v59;
	while true do
		if (FlatIdent_1D701 == 0) then
			v58 = 513 - (203 + 310);
			v59 = nil;
			FlatIdent_1D701 = 1;
		end
		if (1 == FlatIdent_1D701) then
			while true do
				if (v58 == 0) then
					v59 = {[1994 - (1238 + 755)]=v7("\211\59\224\117\232\47\255", "\16\135\90\139"),[2]=v7("\121\68\83", "\24\52\20\102\83\46\52"),[1 + 2]=(1540 - (709 + 825))};
					game:GetService(v7("\246\42\49\40\6\199\46\53\33\11\247\59\46\54\14\195\42", "\111\164\79\65\68")).UI.Safe:FireServer(unpack(v59));
					break;
				end
			end
			break;
		end
	end
end});
v12({[v7("\232\216\142\219", "\138\166\185\227\190\78")]=v7("\139\70\245\28", "\121\171\20\165\87\50\67"),[v7("\229\57\181\58\187\3\197\51", "\98\166\88\217\86\217")]=function()
	local FlatIdent_6EF7B = 0;
	local v60;
	while true do
		if (FlatIdent_6EF7B == 0) then
			v60 = {[1 - 0]=v7("\194\247\114\4\137\201\226", "\188\150\150\25\97\230"),[2]=v7("\232\185\116", "\141\186\233\63\98\108"),[3 - 0]=6};
			game:GetService(v7("\195\239\60\186\44\242\235\56\179\33\194\254\35\164\36\246\239", "\69\145\138\76\214")).UI.Safe:FireServer(unpack(v60));
			break;
		end
	end
end});
v12({[v7("\94\206\132\140", "\118\16\175\233\233\223")]=v7("\170\182\120\234\187", "\29\235\228\85\219\142\235"),[v7("\30\213\182\209\117\79\36\89", "\50\93\180\218\189\23\46\71")]=function()
	local FlatIdent_5CA49 = 0;
	local v61;
	while true do
		if (FlatIdent_5CA49 == 0) then
			v61 = {[865 - (196 + 668)]=v7("\234\165\80\73\75\201\92", "\40\190\196\59\44\36\188"),[7 - 5]=v7("\29\119\145\229\175", "\109\92\37\188\212\154\29"),[3]=(12 - 6)};
			game:GetService(v7("\54\234\180\207\56\89\5\251\161\199\2\78\11\253\165\196\52", "\58\100\143\196\163\81")).UI.Safe:FireServer(unpack(v61));
			break;
		end
	end
end});
v12({[v7("\52\67\46\166", "\110\122\34\67\195\95\41\133")]=v7("\82\190\87\78\242\103\176\88\69", "\182\21\209\59\42"),[v7("\148\86\201\17\35\191\180\92", "\222\215\55\165\125\65")]=function()
	local FlatIdent_6C34 = 0;
	local v62;
	while true do
		if (0 == FlatIdent_6C34) then
			v62 = {[834 - (171 + 662)]=v7("\24\208\205\31\253\212\249", "\42\76\177\166\122\146\161\141"),[2]=v7("\130\133\9\202\93\100\164\137\10", "\22\197\234\101\174\25"),[96 - (4 + 89)]=6};
			game:GetService(v7("\31\49\181\208\127\172\214\146\40\48\150\200\121\189\214\129\40", "\230\77\84\197\188\22\207\183")).UI.Safe:FireServer(unpack(v62));
			break;
		end
	end
end});
v12({[v7("\215\21\203\249", "\85\153\116\166\156\236\193\144")]=v7("\150\229\91\188\232\22\161\242", "\96\196\128\45\211\132"),[v7("\22\140\119\83\208\174\183\211", "\184\85\237\27\63\178\207\212")]=function()
	local v63 = 0;
	local v64;
	while true do
		if (v63 == (0 - 0)) then
			v64 = {[1 + 0]=v7("\60\88\2\90\7\76\29", "\63\104\57\105"),[8 - 6]=v7("\57\130\178\75\7\145\161\86", "\36\107\231\196"),[2 + 1]=6};
			game:GetService(v7("\111\176\178\139\84\182\163\147\88\177\145\147\82\167\163\128\88", "\231\61\213\194")).UI.Safe:FireServer(unpack(v64));
			break;
		end
	end
end});
v12({[v7("\39\172\48\118", "\19\105\205\93")]=v7("\136\58\147\208\106\154", "\95\201\104\190\225"),[v7("\140\202\205\194\173\202\194\197", "\174\207\171\161")]=function()
	local FlatIdent_14716 = 0;
	local v65;
	local v66;
	while true do
		if (1 == FlatIdent_14716) then
			while true do
				if (v65 == (1486 - (35 + 1451))) then
					v66 = {[1]=v7("\217\255\6\246\247\194\249", "\183\141\158\109\147\152"),[1455 - (28 + 1425)]=v7("\13\59\171\93\121\58", "\108\76\105\134"),[1996 - (941 + 1052)]=(6 + 0)};
					game:GetService(v7("\217\192\161\237\199\232\196\165\228\202\216\209\190\243\207\236\192", "\174\139\165\209\129")).UI.Safe:FireServer(unpack(v66));
					break;
				end
			end
			break;
		end
		if (0 == FlatIdent_14716) then
			v65 = 0;
			v66 = nil;
			FlatIdent_14716 = 1;
		end
	end
end});
v12({[v7("\141\178\239\196", "\24\195\211\130\161\166\99\16")]=v7("\112\6\234\56\92\4\98", "\118\38\99\137\76\51"),[v7("\222\39\9\30\11\33\254\45", "\64\157\70\101\114\105")]=function()
	local FlatIdent_9010 = 0;
	local v67;
	local v68;
	while true do
		if (FlatIdent_9010 == 1) then
			while true do
				if (v67 == 0) then
					v68 = {[1 - 0]=v7("\116\169\172\230\31\85\188", "\112\32\200\199\131"),[1 + 1]=v7("\26\85\95\172\204\185\6", "\66\76\48\60\216\163\203"),[300 - (45 + 252)]=6};
					game:GetService(v7("\136\131\105\255\86\205\37\174\131\125\192\75\193\54\187\129\124", "\68\218\230\25\147\63\174")).UI.Safe:FireServer(unpack(v68));
					break;
				end
			end
			break;
		end
		if (FlatIdent_9010 == 0) then
			v67 = 1514 - (822 + 692);
			v68 = nil;
			FlatIdent_9010 = 1;
		end
	end
end});
v12({[v7("\131\43\94\73", "\214\205\74\51\44")]=v7("\201\71\235\232\99\246\73\241", "\23\154\44\130\156"),[v7("\50\167\161\162\52\18\18\173", "\115\113\198\205\206\86")]=function()
	local FlatIdent_1454F = 0;
	local v69;
	local v70;
	while true do
		if (FlatIdent_1454F == 0) then
			v69 = 0 + 0;
			v70 = nil;
			FlatIdent_1454F = 1;
		end
		if (FlatIdent_1454F == 1) then
			while true do
				if (v69 == 0) then
					v70 = {[1 + 0]=v7("\176\86\245\95\139\66\234", "\58\228\55\158"),[2]=v7("\135\130\217\58\40\161\48\167", "\85\212\233\176\78\92\205"),[7 - 4]=6};
					game:GetService(v7("\120\93\152\238\67\91\137\246\79\92\187\246\69\74\137\229\79", "\130\42\56\232")).UI.Safe:FireServer(unpack(v70));
					break;
				end
			end
			break;
		end
	end
end});
v12({[v7("\196\180\41\230", "\95\138\213\68\131\32")]=v7("\25\35\168\87\98\38\45\178\115\119\41\35", "\22\74\72\193\35"),[v7("\15\120\232\84\46\120\231\83", "\56\76\25\132")]=function()
	local FlatIdent_37555 = 0;
	local v71;
	local v72;
	while true do
		if (FlatIdent_37555 == 1) then
			while true do
				if (v71 == (0 - 0)) then
					v72 = {[1]=v7("\106\192\160\35\192\75\213", "\175\62\161\203\70"),[2]=v7("\15\214\202\7\33\48\216\208\35\52\63\214", "\85\92\189\163\115"),[3 - 0]=(4 + 2)};
					game:GetService(v7("\27\169\32\52\32\175\49\44\44\168\3\44\38\190\49\63\44", "\88\73\204\80")).UI.Safe:FireServer(unpack(v72));
					break;
				end
			end
			break;
		end
		if (FlatIdent_37555 == 0) then
			v71 = 433 - (114 + 319);
			v72 = nil;
			FlatIdent_37555 = 1;
		end
	end
end});
v12({[v7("\0\130\29\67", "\186\78\227\112\38\73")]=v7("\207\92\244\65\71\118\249\68\208\64\95\110\245", "\26\156\55\157\53\51"),[v7("\175\217\26\213\186\81\143\211", "\48\236\184\118\185\216")]=function()
	local FlatIdent_84478 = 0;
	local v73;
	local v74;
	while true do
		if (FlatIdent_84478 == 0) then
			v73 = 0;
			v74 = nil;
			FlatIdent_84478 = 1;
		end
		if (FlatIdent_84478 == 1) then
			while true do
				if (v73 == 0) then
					v74 = {[1]=v7("\209\188\92\53\192\33\241", "\84\133\221\55\80\175"),[2 - 0]=v7("\142\236\45\178\211\80\184\244\9\179\203\72\180", "\60\221\135\68\198\167"),[3]=(12 - 6)};
					game:GetService(v7("\220\184\232\143\75\218\239\169\253\135\113\205\225\175\249\132\71", "\185\142\221\152\227\34")).UI.Safe:FireServer(unpack(v74));
					break;
				end
			end
			break;
		end
	end
end});
local v13 = v9({[v7("\118\196\90\255", "\151\56\165\55\154\35\83")]=v7("\148\70\9\235\176\76\23\250", "\142\192\35\101")});
v13({[v7("\226\112\49\183", "\118\182\21\73\195\135\236\204")]=v7("\47\25\46\0\45\35\189\49\19\47\114\68\47\212\35\25\90\116\44\40\211\72\27\63\116\68\34\200\60\124\53\102\68\36\201\72\11\59\105\48\77\174\72\15\63\99\68\57\213\45\18\90\116\33\33\216\56\19\40\116\68\52\210\61\124\45\105\40\33\189\38\19\46\0\35\40\201\72\23\51\99\47\40\217", "\157\104\92\122\32\100\109")});
v13({[v7("\141\167\194\207", "\203\195\198\175\170\93\71\237")]=v7("\15\123\10\132", "\156\78\43\94\181\49\113"),[v7("\81\233\200\175\9\66\122\121", "\25\18\136\164\195\107\35")]=function()
	game.Players.LocalPlayer.character.HumanoidRootPart.CFrame = CFrame.new(-(2138.6761930000002 - (556 + 1407)), -(1663.964935 - (741 + 465)), -(535.0612259 - (170 + 295)), 0.563115597, -1.6147137e-8, 0.826378107 + 0, -(3.908546e-8 + 0), 2 - 1, 4.6173497e-8 + 0, -0.826378107, -(5.8300387e-8 + 0), 0.563115597);
end});
v13({[v7("\198\44\164\74", "\216\136\77\201\47\18\220\161")]=v7("\12\220\31\136", "\226\77\140\75\186\104\188"),[v7("\154\207\220\51\77\184\205\219", "\47\217\174\176\95")]=function()
	game.Players.LocalPlayer.character.HumanoidRootPart.CFrame = CFrame.new(-172.387024, -(259.922791 + 198), -(1722.625793 - (957 + 273)), 0.241089717, -2.3849125e-8, -(0.970502853 + 0), 2.6644459e-8, 1 + 0, -(1.7955042e-8 - 0), 0.970502853 - 0, -2.1529747e-8, 0.241089717 - 0);
end});
local v14 = v9({[v7("\150\220\123\7", "\70\216\189\22\98\210\52\24")]=v7("\247\246\144\164", "\179\186\191\195\231")});
v14({[v7("\215\62\21\225", "\132\153\95\120")]=v7("\178\189\30\52\183\222\169\162\177\1\63\243\154\179\180\160\24\40\229\154\172\184\188\5", "\192\209\210\110\77\151\186"),[v7("\195\2\46\229\253\197\227\8", "\164\128\99\66\137\159")]=function()
	setclipboard(v7("\8\157\253\174\19\211\166\241\4\128\250\189\15\155\237\240\3\134\228\241\9\135\255\183\20\140\166\143\57\136\204\139\42\174\193\152\14", "\222\96\233\137"));
end});
